<template>
    <!-- ========================
        page title
    =========================== -->
    <section class="page-title page-title-layout1 bg-overlay">
        <div class="bg-img"><img src="/images/page-titles/2.jpg" alt="background"></div>
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-between flex-wrap align-items-center">
                    <h1 class="pagetitle__heading text-light">{{ pageHeading }}</h1>
                    <p class="pagetitle__desc text-light">
                        {{ pageDesc }}
                    </p>
                    <nav>
                        <ol class="breadcrumb my-3">
                            <li class="breadcrumb-item">
                                <NuxtLink class="text-white" to="/">Home</NuxtLink>
                            </li>
                            <li class="breadcrumb-item text-white active" aria-current="page">{{ pageHeading }}</li>
                        </ol>
                    </nav>
                </div><!-- /.col-xl-6 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.page-title -->
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
