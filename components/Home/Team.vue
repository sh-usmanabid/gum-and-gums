<template>
    <!-- ======================
        Team
    ========================= -->
    <section class="team-layout1 pb-80 mt--100">
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-12 col-lg-6 offset-lg-3">
                    <div class="heading text-center mb-40">
                        <h3 class="heading__title">Meet Our Doctors</h3>
                        <p class="heading__desc">Our administration and support staff all have exceptional people skills
                            and
                            trained to assist you with all medical enquiries.
                        </p>
                    </div><!-- /.heading -->
                </div><!-- /.col-lg-6 -->
            </div><!-- /.row -->
            <div class="row">
                <div class="col-12">
                    <div class="row">
                        <!-- Member #1 -->
                        <div class="member col-md-4">
                            <div class="member__img">
                                <img src="/images/team/1.jpg" alt="member img">
                                <ul class="social-icons list-unstyled mb-0">
                                    <li><a href="#" class="facebook"><i class="fab fa-facebook-f"></i></a></li>
                                    <li><a href="#" class="twitter"><i class="fab fa-twitter"></i></a></li>
                                    <li><a href="#" class="phone"><i class="fas fa-phone-alt"></i></a></li>
                                </ul><!-- /.social-icons -->
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name"><a href="#">Mike Dooley</a></h5>
                                <p class="member__job">Cardiology Specialist</p>
                                <p class="member__desc">Muldoone obtained his undergraduate degree in Biomedical
                                    Engineering at Tulane
                                    University prior to attending St George's University School of Medicine</p>
                                <div class="mt-20 d-flex flex-wrap justify-content-between align-items-center">
                                    <a href="#"
                                        class="btn btn__secondary btn__link btn__rounded">
                                        <span>Read More</span>
                                        <i class="icon-arrow-right"></i>
                                    </a>
                                </div>
                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                        <!-- Member #2 -->
                        <div class="member col-md-4">
                            <div class="member__img">
                                <img src="/images/team/2.jpg" alt="member img">
                                <ul class="social-icons list-unstyled mb-0">
                                    <li><a href="#" class="facebook"><i class="fab fa-facebook-f"></i></a></li>
                                    <li><a href="#" class="twitter"><i class="fab fa-twitter"></i></a></li>
                                    <li><a href="#" class="phone"><i class="fas fa-phone-alt"></i></a></li>
                                </ul><!-- /.social-icons -->
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name"><a href="#">Dermatologists</a></h5>
                                <p class="member__job">Cardiology Specialist</p>
                                <p class="member__desc">Brian specializes in treating skin, hair, nail, and mucous
                                    membrane. He also
                                    address cosmetic issues, helping to revitalize the appearance of the skin</p>
                                <div class="mt-20 d-flex flex-wrap justify-content-between align-items-center">
                                    <a href="#"
                                        class="btn btn__secondary btn__link btn__rounded">
                                        <span>Read More</span>
                                        <i class="icon-arrow-right"></i>
                                    </a>
                                </div>
                            </div><!-- /.member-info -->
                        </div><!-- /.member -->
                        <!-- Member #3 -->
                        <div class="member col-md-4">
                            <div class="member__img">
                                <img src="/images/team/3.jpg" alt="member img">
                                <ul class="social-icons list-unstyled mb-0">
                                    <li><a href="#" class="facebook"><i class="fab fa-facebook-f"></i></a></li>
                                    <li><a href="#" class="twitter"><i class="fab fa-twitter"></i></a></li>
                                    <li><a href="#" class="phone"><i class="fas fa-phone-alt"></i></a></li>
                                </ul><!-- /.social-icons -->
                            </div><!-- /.member-img -->
                            <div class="member__info">
                                <h5 class="member__name"><a href="#">Maria Andaloro</a></h5>
                                <p class="member__job">Pediatrician</p>
                                <p class="member__desc">Andaloro graduated from medical school and completed 3 years
                                    residency program
                                    in pediatrics. She passed rigorous exams by the American Board of Pediatrics.</p>
                                <div class="mt-20 d-flex flex-wrap justify-content-between align-items-center">
                                    <a href="#"
                                        class="btn btn__secondary btn__link btn__rounded">
                                        <span>Read More</span>
                                        <i class="icon-arrow-right"></i>
                                    </a>
                                </div>
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

<style>
.team-layout1 {
    z-index: 100;
}
</style>