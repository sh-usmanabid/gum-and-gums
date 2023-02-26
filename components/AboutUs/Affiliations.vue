<template>
    <!-- ========================
        Affiliations
    =========================== -->
    <section class="gallery pt-90 pb-60">
        <div class="heading text-center mb-40">
            <h3 class="heading__title">Accolades & Affiliations</h3>
        </div><!-- /.heading -->
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <VueSlickCarousel v-bind="settings">
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-1.png">
                            <img src="/images/gallery/image-1.png" alt="gallery img" height="75">
                        </a>

                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-4.png">
                            <img src="/images/gallery/image-4.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-5.png">
                            <img src="/images/gallery/image-5.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-6.png">
                            <img src="/images/gallery/image-6.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-7.png">
                            <img src="/images/gallery/image-7.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-8.png">
                            <img src="/images/gallery/image-8.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-9.png">
                            <img src="/images/gallery/image-9.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-10.png">
                            <img src="/images/gallery/image-10.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-11.png">
                            <img src="/images/gallery/image-11.png" alt="gallery img" height="75">
                        </a>
                      <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-15.png">
                        <img src="/images/gallery/image-15.png" alt="gallery img" height="75">
                      </a>
                      <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-16.png">
                        <img src="/images/gallery/image-16.png" alt="gallery img" height="75">
                      </a>
                      <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-17.png">
                        <img src="/images/gallery/image-17.png" alt="gallery img" height="75">
                      </a>

                    </VueSlickCarousel><!-- /.carousel -->
                </div><!-- /.col-xl-5 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Affiliations -->
</template>

<script>
export default {
    data() {
        return {
            settings: {
                "slidesToShow": 4,
                "slidesToScroll": 1,
                "autoplay": true,
                "arrows": true,
                "dots": false,
                "responsive": [
                    {"breakpoint": 992, "settings": {"slidesToShow": 2}},
                    {"breakpoint": 767, "settings": {"slidesToShow": 2}},
                    {"breakpoint": 480, "settings": {"slidesToShow": 1}}
                ]
            }
        }
    }
}
</script>
