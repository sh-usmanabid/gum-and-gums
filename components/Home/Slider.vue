<template>
    <!-- ============================
        Slider
    ============================== -->
    <section class="slider">
        <div class="m-slides-0">
            <div class="slide-item align-v-h">
                <div class="bg-img"><img src="/images/sliders/2.jpg" alt="slide img"></div>
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-sm-12 col-md-8 col-lg-6 col-xl-6">
                            <div class="slide__content">
                                <h2 class="slide__title" style="color:white;">World's first device that flosses all of
                                    your teeth at once.</h2>
                                <p class="slide__desc" style="color:white;">Dr. Floss is the world's first one size fits
                                    all floss solution which carries the mission of making flossing easy.</p>
                            </div><!-- /.slide-content -->
                        </div><!-- /.col-xl-7 -->
                        <div class="col-sm-12 col-md-8 col-lg-6 col-xl-6">
                            <img src="/product.png" />
                        </div>
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.slide-item -->
        </div><!-- /.carousel -->
    </section><!-- /.slider -->
</template>

<script>
export default {
    props: ['pageHeading', 'pageDesc'],
    mounted() {
        $('.bg-img').each(function () {
            const imgSrc = $(this).children('img').attr('src')
            $(this).parent().css({
                'background-image': 'url(' + imgSrc + ')',
                'background-size': 'cover',
                'background-position': 'center'
            })
            $(this).parent().addClass('bg-img')
            if ($(this).hasClass('background-size-auto')) {
                $(this).parent().addClass('background-size-auto')
            }
            $(this).remove()
        })
    }
}
</script>