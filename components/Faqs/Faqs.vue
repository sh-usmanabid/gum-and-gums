<template>
    <!-- ======================
        FAQ
    ========================= -->
    <section class="faq pt-120 pb-70">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-12" id="accordion">
                    <div class="accordion-item opened">
                        <div class="accordion__header" role="tab" data-toggle="collapse" aria-expanded="true" aria-controls="collapse1" data-target="#collapse1">
                            <a class="accordion__title" href="#collapse1">How does Dr. Floss work?</a>
                        </div><!-- /.accordion-item-header -->
                        <div id="collapse1" class="collapse show" data-parent="#accordion">
                            <div class="accordion__body">
                                <p> It is a one-step solution that can easily be placed in and out of the mouth to floss the teeth. Additionally, the frame can be rotated from the front holder for a more comprehensive cleaning.</p>
                            </div><!-- /.accordion-item-body -->
                        </div>
                    </div><!-- /.accordion-item -->
                    <div class="accordion-item">
                        <div class="accordion__header" role="tab" data-toggle="collapse" aria-expanded="false" aria-controls="collapse2" data-target="#collapse2">
                            <a class="accordion__title" href="#collapse2">What advantages does Dr. Floss offer?</a>
                        </div><!-- /.accordion-item-header -->
                        <div id="collapse2" class="collapse" data-parent="#accordion">
                            <div class="accordion__body">
                                <p>Dr. Floss prevents cross-contamination by cleaning each tooth with individual threads as it is single-use. Although disposable, it is made from biodegradable materials and comes in eco-friendly packaging, making it an environmentally-friendly option.n</p>
                            </div><!-- /.accordion-item-body -->
                        </div>
                    </div><!-- /.accordion-item -->
                    <div class="accordion-item">
                        <div class="accordion__header" role="tab" data-toggle="collapse" aria-expanded="false" aria-controls="collapse3" data-target="#collapse3">
                            <a class="accordion__title" href="#collapse3">What is the recommended usage for optimal results with your product?</a>
                        </div><!-- /.accordion-item-header -->
                        <div id="collapse3" class="collapse" data-parent="#accordion">
                            <div class="accordion__body">
                                <p>A single disposable top frame should be used and replaced with a fresh pair for both the top and bottom arch of teeth. It is suggested to floss twice a day as recommended by dentists.</p>
                            </div><!-- /.accordion-item-body -->
                        </div>
                    </div><!-- /.accordion-item -->
                    <div class="accordion-item">
                        <div class="accordion__header" role="tab" data-toggle="collapse" aria-expanded="false" aria-controls="collapse4" data-target="#collapse4">
                            <a class="accordion__title" href="#collapse4">Are there any precautions to take or warnings when using your product?</a>
                        </div><!-- /.accordion-item-header -->
                        <div id="collapse4" class="collapse" data-parent="#accordion">
                            <div class="accordion__body">
                                <p>It is important to not reuse the same disposable top frame as it may lead to cross-contamination of bacteria between teeth.</p>
                            </div><!-- /.accordion-item-body -->
                        </div>
                    </div><!-- /.accordion-item -->
                    <div class="accordion-item">
                        <div class="accordion__header" role="tab" data-toggle="collapse" aria-expanded="false" aria-controls="collapse5" data-target="#collapse5">
                            <a class="accordion__title" href="#collapse5">How can I determine if your product is the appropriate size for me?</a>
                        </div><!-- /.accordion-item-header -->
                        <div id="collapse5" class="collapse" data-parent="#accordion">
                            <div class="accordion__body">
                                <p>Similar to a mouth guard, we currently offer a single adult size that is a universal fit for all adult individuals, regardless of gender.</p>
                            </div><!-- /.accordion-item-body -->
                        </div>
                    </div><!-- /.accordion-item -->
                </div><!-- /.col-lg-8 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.FAQ -->
</template>

<script>
export default {
  mounted() {
    $('.accordion__header').on('click', function () {
        $(this).parent('.accordion-item').toggleClass('opened')
        $(this).parent('.accordion-item').siblings().removeClass('opened')
        $(this).parent('.accordion-item').children('.collapse').toggleClass('show')
        
        $('.collapse').removeClass('show')
        $(this).parent('.accordion-item').children('.collapse').toggleClass('show')
    })
    $('.accordion__title').on('click', function (e) {
        e.preventDefault()
    })
  }
}
</script>