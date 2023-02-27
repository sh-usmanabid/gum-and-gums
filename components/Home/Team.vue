<template>
    <!-- ======================
        Team
    ========================= -->
    <section class="team-layout1 pb-80 mt--100">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-6 offset-lg-3">
                    <div class="heading text-center mb-40">
                        <h3 class="heading__title">Hear From Experts</h3>
                        <p class="heading__desc">Here's what the dentists have to say about Dr. Floss
                        </p>
                    </div><!-- /.heading -->
                </div><!-- /.col-lg-6 -->
            </div><!-- /.row -->
            <div class="row">
                <div class="col-12">
                    <div class="row container member-container">
                        <!-- Member #1 -->
                        <div class="member col-md-6">
                            <div class="member__img">
                                <img src="/images/team/1.jpg" alt="member img">
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name">Dr. Zakia Anjum Akhtar</h5>
                                <p class="member__job">DDS (NYU), Residency (St. Vincent's Medical Center)</p>
                                <p class="member__desc">Flossing is difficult for most patients.  DR. FLOSS is a great alternative for those patients that have a hard time time using regular string floss.  Being that you "floss" all teeth at once, there is little to no bacteria transfer from site to site in comparison to traditional dental picks.  And it's definitely alot less time consuming.</p>
                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                        <div class="member col-md-6">
                            <div class="member__img">
                                <img src="/images/team/2.jpg" alt="member img">
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name">Dr. Rashid Mahmood</h5>
                                <p class="member__job">DBDS Dental Surgeon & Orthodontist</p>
                                <p class="member__desc">Dr. Floss will indeed be a revolutionary replacement of conventional flossing, its unique and innovative design will be a choice for those who want quick and easy way to maintain their oral hygiene.</p>
                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                    </div><!-- /.carousel -->
                </div><!-- /.col-12 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Team -->
</template>

<script>
export default {
    data() {
        return {
            settings: {
                "slidesToShow": 3,
                "slidesToScroll": 1,
                "autoplay": true,
                "arrows": false,
                "dots": false,
                "responsive": [
                    {"breakpoint": 992, "settings": {"slidesToShow": 2}},
                    {"breakpoint": 767, "settings": {"slidesToShow": 1}},
                    {"breakpoint": 480, "settings": {"slidesToShow": 1}}
                ]
            }
        }
    }
}
</script>

<style scoped>
.team-layout1 {
    z-index: 100;
}

.member {
    max-width: 500px;
    padding: 0px !important;
    margin: 25px auto;
    box-shadow: 0px 5px 5px 0px rgba(9, 29, 62, 0.15);
}

.member img {
    width: 100% !important;
}

.member-container {
    text-align: center;
    margin: 0 auto;
}
</style>
