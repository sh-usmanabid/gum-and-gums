<template>
    <!-- Post Item #1 -->
    <div class="col-sm-12 col-md-6 col-lg-4">
        <div class="post-item">
            <div class="post__img">
                <NuxtLink :to="{path: blogLink,query:{blogImage:blogImage,blogTitle:blogTitle,blogDesc:blogDesc}}">
                    <img :src="blogImage" alt="post image" loading="lazy">
                </NuxtLink>
            </div><!-- /.post__img -->
            <div class="post__body pt-5">
                <h4 class="post__title"><NuxtLink :to="{path: blogLink,query:{blogImage:blogImage,blogTitle:blogTitle,blogDesc:blogDesc}}">{{ blogTitle }}</NuxtLink></h4>

                <p class="post__desc">{{ blogDesc }}</p>
                <NuxtLink :to="{path: blogLink,query:{blogImage:blogImage,blogTitle:blogTitle,detailDesc:detailDesc}}" class="btn btn__secondary btn__link btn__rounded">
                    <span>Read More</span>
                    <i class="icon-arrow-right"></i>
                </NuxtLink>
            </div><!-- /.post__body -->
        </div><!-- /.post-item -->
    </div><!-- /.col-lg-4 -->
</template>

<script>
export default {
    props: ['blogImage', 'blogTitle', 'blogDesc', 'blogLink','detailDesc']
}
</script>
