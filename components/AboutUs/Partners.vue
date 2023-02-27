<template>
    <!-- ========================
        Partners
    =========================== -->
    <section class="gallery pt-0 pb-90">
        <div class="heading text-center mb-40">
            <h3 class="heading__title">Global Product Developement Partners</h3>
        </div><!-- /.heading -->
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <carousel :loop="true" :margin=20 :nav="false" :dots="false" :smartSpeed=300 :autoplay="false" :responsive="res">
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-2.png">
                          <img src="/images/gallery/image-2.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-3.png">
                          <img src="/images/gallery/image-3.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-12.png">
                          <img src="/images/gallery/image-12.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-13.png">
                          <img src="/images/gallery/image-13.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-14.png">
                            <img src="/images/gallery/image-14.png" alt="gallery img" height="75">
                        </a>

                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-18.png">
                            <img src="/images/gallery/image-18.png" alt="gallery img" height="75">
                        </a>
                    </carousel><!-- /.carousel -->
                </div><!-- /.col-xl-5 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Partners -->

</template>

<script>
export default {
    data() {
        return {
            res: {
                0: {
                    items: 1
                },
                480: {
                    items: 2
                },
                600: {
                    items: 3
                },
                800: {
                    items: 4
                },
                1024: {
                    items: 5
                }
            }
        }
    }
}
</script>
