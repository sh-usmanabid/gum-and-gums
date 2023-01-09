<template>
    <!-- ========================
        Affiliations
    =========================== -->
    <section class="gallery pt-90 pb-60">
        <div class="heading text-center mb-40">
            <h3 class="heading__title">Accolades & Affiliations</h3>
            <p class="heading__desc">Startup Montclair Pitch Contest 1st 2020.<br />TIE UNIVERSITY: Best Startup Idea
                Award 2021, 3rd Place 2022.
            </p>
        </div><!-- /.heading -->
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <VueSlickCarousel v-bind="settings">
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-1.png">
                            <img src="/images/gallery/image-1.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-2.png">
                            <img src="/images/gallery/image-2.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-3.png">
                            <img src="/images/gallery/image-3.png" alt="gallery img" height="75">
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
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-12.png">
                            <img src="/images/gallery/image-12.png" alt="gallery img" height="75">
                        </a>
                        <a class="popup-gallery-item text-center p-5" href="/images/gallery/image-13.png">
                            <img src="/images/gallery/image-13.png" alt="gallery img" height="75">
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