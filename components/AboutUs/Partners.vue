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
                    <VueSlickCarousel v-bind='settings'>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-14.png">
                            <img src="/images/gallery/image-14.png" alt="gallery img" height="75">
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
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-18.png">
                            <img src="/images/gallery/image-18.png" alt="gallery img" height="75">
                        </a>
                    </VueSlickCarousel><!-- /.carousel -->
                </div><!-- /.col-xl-5 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Partners -->

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