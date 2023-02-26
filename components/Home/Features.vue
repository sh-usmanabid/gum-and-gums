<template>
    <!-- ======================
        Features
    ========================= -->
    <section class="features-layout2 pt-130">
        <div class="bg-img"><img src="/images/backgrounds/1.jpg" alt="background"></div>
        <div class="container">
            <div class="heading_layout2">
                <h3 class="heading__title" style="text-align: center;">Product Features</h3>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="carousel-container mt-90">
                        <VueSlickCarousel class="feature-slider" v-bind='settings'>
                            <div class="process-item">
                                <span class="process__number">01</span>
                                <div class="process__icon">
                                    <img src="/images/features/1.png"/>
                                </div><!-- /.process__icon -->
                                <h4 class="process__title">Eliminates Incorrect user Techniques</h4>
                                <p class="process__desc">Avoid common mistakes and improve your flossing skills.</p>
                            </div><!-- /.process-item -->
                            <div class="process-item">
                                <span class="process__number">02</span>
                                <div class="process__icon">
                                    <img src="/images/features/1.png"/>
                                </div><!-- /.process__icon -->
                                <h4 class="process__title">Ergonomic Design</h4>
                                <p class="process__desc">Experience comfort and ease with our ergonomically designed product.</p>
                            </div><!-- /.process-item -->
                            <div class="process-item">
                                <span class="process__number">03</span>
                                <div class="process__icon">
                                    <img src="/images/features/1.png"/>
                                </div><!-- /.process__icon -->
                                <h4 class="process__title">Fast Cleaning</h4>
                                <p class="process__desc">Quickly and easily remove plaque with our fast-acting floss.</p>
                            </div><!-- /.process-item -->
                            <div class="process-item">
                                <span class="process__number">04</span>
                                <div class="process__icon">
                                    <img src="/images/features/1.png"/>
                                </div><!-- /.process__icon -->
                                <h4 class="process__title">Eco-Friendly Packaging</h4>
                                <p class="process__desc">Reduce your environmental impact with our eco-friendly packaging options.</p>
                            </div><!-- /.process-item -->
                            <div class="process-item">
                                <span class="process__number">05</span>
                                <div class="process__icon">
                                    <img src="/images/features/1.png"/>
                                </div><!-- /.process__icon -->
                                <h4 class="process__title">Accessible For All</h4>
                                <p class="process__desc">Our product is designed for everyone, no matter your ability.</p>
                            </div><!-- /.process-item -->
                        </VueSlickCarousel><!-- /.carousel -->
                    </div>
                </div><!-- /.col-12 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Features -->
</template>

<script>
export default {
    data() {
        return {
            settings: {
                "slidesToShow": 4,
                "slidesToScroll": 1,
                "arrows": false,
                "dots": false,
                "responsive": [
                    { "breakpoint": 1200, "settings": { "slidesToShow": 3 } },
                    { "breakpoint": 992, "settings": { "slidesToShow": 2 } },
                    { "breakpoint": 767, "settings": { "slidesToShow": 2 } },
                    { "breakpoint": 480, "settings": { "slidesToShow": 1 } }
                ]
            }
        }
    }
}
</script>

<style>
@media only screen and (min-width: 993px) {
    .features-layout1 {
        height: 750px;
    }
}

@media only screen and (max-width: 992px) {
    .features-layout1 {
        height: 600px;
    }
}

.process-item {
    height: 300px !important;
}

.feature-slider {
    height: 300px;
}
</style>
