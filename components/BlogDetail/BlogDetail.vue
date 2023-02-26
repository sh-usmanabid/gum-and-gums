<template>
  <div>
    <section class="page-title pt-30 pb-30 text-center">
      <div class="container">
        <div class="row align-items-center">
        </div><!-- /.row -->
      </div><!-- /.container -->
    </section><!-- /.page-title -->

    <section class="blog blog-single pt-0 pb-80">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-12 col-lg-12">
            <div class="post-item mb-0">
              <div class="post__img">
                <a href="#">
                  <img :src="blogImage" alt="post image" loading="lazy">
                </a>
              </div><!-- /.post-img -->
              <div class="post__body pb-0">
                <div class="post__meta-cat">
                </div><!-- /.blog-meta-cat -->
                <div class="post__meta d-flex align-items-center mb-20">

                </div><!-- /.blog-meta -->
                <h1 class="post__title mb-30">
                  {{blogTitle }}
                </h1>
                <div class="post__desc">
                  <p style="white-space: pre-wrap;">{{detailDesc}}</p>
                </div><!-- /.blog-desc -->
              </div>
            </div><!-- /.post-item -->

          </div><!-- /.col-lg-8 -->
        </div><!-- /.row -->
      </div><!-- /.container -->
    </section><!-- /.blog Single -->
  </div>
</template>

<script>
export default {
  name: "BlogDetail",
  props:['detailDesc','blogTitle','blogImage']
}
</script>

<style scoped>

</style>
