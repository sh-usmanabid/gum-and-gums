<template>
    <!-- ==========================
        Contact layout 1
    =========================== -->
    <section class="contact-layout1 pt-0 mt--100">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="contact-panel d-flex flex-wrap">
                        <form class="contact-panel__form" method="post" action="assets/php/contact.php"
                            id="contactForm">
                            <div class="row">
                                <div class="col-sm-12">
                                    <h4 class="contact-panel__title">How Can We Help? </h4>
                                    <p class="contact-panel__desc mb-30">Please feel welcome to contact our friendly
                                        reception staff
                                        with any general or medical enquiry. Our doctors will receive or return any
                                        urgent calls.
                                    </p>
                                </div>
                                <div class="col-sm-6 col-md-6 col-lg-6">
                                    <div class="form-group">
                                        <i class="icon-user form-group-icon"></i>
                                        <input type="text" class="form-control" placeholder="Name" id="contact-name"
                                            name="contact-name" required>
                                    </div>
                                </div><!-- /.col-lg-6 -->
                                <div class="col-sm-6 col-md-6 col-lg-6">
                                    <div class="form-group">
                                        <i class="icon-email form-group-icon"></i>
                                        <input type="email" class="form-control" placeholder="Email" id="contact-email"
                                            name="contact-email" required>
                                    </div>
                                </div><!-- /.col-lg-6 -->
                                <div class="col-12">
                                    <div class="form-group">
                                        <i class="icon-phone form-group-icon"></i>
                                        <input type="text" class="form-control" placeholder="Phone" id="contact-Phone"
                                            name="contact-phone" required>
                                    </div>
                                </div><!-- /.col-12 -->
                                <div class="col-12">
                                    <div class="form-group">
                                        <i class="icon-alert form-group-icon"></i>
                                        <textarea class="form-control" placeholder="Message" id="contact-message"
                                            name="contact-message"></textarea>
                                    </div>
                                    <button type="submit"
                                        class="btn btn__secondary btn__rounded btn__block btn__xhight mt-10">
                                        <span>Submit Request</span> <i class="icon-arrow-right"></i>
                                    </button>
                                    <div class="contact-result"></div>
                                </div><!-- /.col-lg-12 -->
                            </div><!-- /.row -->
                        </form>
                        <div
                            class="contact-panel__info d-flex flex-column justify-content-between bg-overlay bg-overlay-primary-gradient">
                            <div class="bg-img"><img src="assets/images/banners/1.jpg" alt="banner"></div>
                            <div>
                                <h4 class="contact-panel__title color-white">Quick Contacts</h4>
                                <p class="contact-panel__desc font-weight-bold color-white mb-30">Please feel free to
                                    contact our
                                    friendly staff with any medical enquiry.
                                </p>
                            </div>
                            <div>
                                <ul class="contact__list list-unstyled mb-30">
                                    <li>
                                        <i class="icon-phone"></i><a href="tel:+5565454117">Emergency Line: (+1)
                                            2012904909</a>
                                    </li>
                                    <li>
                                        <i class="icon-location"></i><a href="#">Location: 1 Normal Ave. Montclair, NJ
                                            07043</a>
                                    </li>
                                </ul>
                                <a href="#" class="btn btn__white btn__rounded btn__outlined">Contact Us</a>
                            </div>
                        </div>
                    </div>
                </div><!-- /.col-lg-6 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.Contact -->
</template>