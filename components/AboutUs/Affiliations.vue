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
                    <carousel :loop="true" :margin=20 :nav="false" :dots="false" :smartSpeed=300 :autoplay="false" :responsive="res">
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

                    </carousel><!-- /.carousel -->
                </div><!-- /.col-xl-5 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Affiliations -->
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