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
                    <div class="row">
                        <!-- Member #1 -->
                      <div class="col-md-2"></div>
                        <div class="member col-md-4">
                            <div class="member__img">
                                <img src="/images/team/1.jpg" alt="member img">
<!--                                <ul class="social-icons list-unstyled mb-0">-->
<!--                                    <li><a href="#" class="facebook"><i class="fab fa-facebook-f"></i></a></li>-->
<!--                                    <li><a href="#" class="twitter"><i class="fab fa-twitter"></i></a></li>-->
<!--                                    <li><a href="#" class="phone"><i class="fas fa-phone-alt"></i></a></li>-->
<!--                                </ul>&lt;!&ndash; /.social-icons &ndash;&gt;-->
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name"><a href="#">Dr. Zakia Anjum Akhtar</a></h5>
<!--                                <p class="member__job">Cardiology Specialist</p>-->
                                <p class="member__desc">Flossing is difficult for most patients.  DR. FLOSS is a great alternative for those patients that have a hard time time using regular string floss.  Being that you "floss" all teeth at once, there is little to no bacteria transfer from site to site in comparison to traditional dental picks.  And it's definitely alot less time consuming.</p>

                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                        <!-- Member #2 -->
                        <div class="member col-md-4">
                            <div class="member__img">
                                <img src="/images/team/2.jpg" alt="member img">
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name"><a href="#">Dr. Rashid Mahmood</a></h5>
                                <p class="member__job">BDS Dental Surgeon & Orthodontist</p>
                                <p class="member__desc">Dr. Floss will indeed be a revolutionary replacement of conventional flossing, its unique and innovative design will be a choice for those who want quick and easy way to maintain their oral hygiene.</p>
                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                        <!-- Member #3 -->
                      <div class="col-md-2"></div>
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

<style>
.team-layout1 {
    z-index: 100;
}
</style>
