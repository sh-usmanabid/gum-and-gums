<template>
    <!-- ========================
        About Layout 1
    =========================== -->
    <section class="about-layout1 pb-130 pt-130">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-6">
                    <div class="heading-layout2">
                        <h3 class="heading__title mb-40">How Does It Work?</h3>
                    </div><!-- /heading -->
                </div><!-- /.col-12 -->
            </div><!-- /.row -->
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-6">
                    <div class="about__Text">
                        <p class="mb-30">Gum & Gums has innovated an all at once flossing device
                            which you can simply pop in & out of your mouth while seamlessly flossing all of your teeth
                            simultaneously.
                        </p>
                    </div>
                    <p class="mb-30">Gum & Gums is a Sustainable Oral Hygiene brand that has reinvented the wheel around flossing all of your teeth simultaneously with its premier product Dr. Floss. It is the world’s first one size fits all solution. Enabling ethical sustainability, we aim to achieve this by using Biodegradable materials and Eco-friendly packaging for our products.</p>
                    <NuxtLink to="shop" class="btn btn__primary btn__rounded">
                        <span>Learn More</span>
                        <i class="icon-arrow-right"></i>
                    </NuxtLink>
                </div><!-- /.col-lg-6 -->
                <div class="col-sm-12 col-md-12 col-lg-6">
                    <div class="video-banner">
                        <iframe width="100%" height="315" src="https://www.youtube.com/embed/Wl-hrUx5kyk"
                            title="YouTube video player" frameborder="0"
                            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                            allowfullscreen></iframe>
                    </div><!-- /.video-banner -->
                </div><!-- /.col-lg-6 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.About Layout 1 -->
</template>

<style scoped>
@media only screen and (min-width: 992px) {
    iframe {
        margin-top: -80px;
    }
}

@media only screen and (max-width: 991px) {
    iframe {
        margin-top: 25px;
    }
}
</style>