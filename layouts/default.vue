<template>
    <div class="wrapper">
        <!-- =========================
            Header
        =========================== -->
        <header class="header header-layout2">
            <nav class="navbar navbar-expand-lg sticky-navbar">
                <div class="container-fluid">
                    <NuxtLink class="navbar-brand" to="/">
                        <img src="/images/logo/logo-light.png" class="logo-light" alt="logo"
                            style="height:50px;width:185px;">
                        <img src="/images/logo/logo-dark.png" class="logo-dark" alt="logo"
                            style="height:50px;width:185px;">
                    </NuxtLink>
                    <button class="navbar-toggler" type="button">
                        <span class="menu-lines"><span></span></span>
                    </button>
                    <div class="collapse navbar-collapse" id="mainNavigation">
                        <ul class="navbar-nav ml-auto">
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/" :class="($nuxt.$route.name === 'index') ? 'nav__item-link active': 'nav__item-link'">Home</NuxtLink>
                            </li><!-- /.nav-item -->
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/about-us" :class="($nuxt.$route.name === 'about-us') ? 'nav__item-link active': 'nav__item-link'">About The Founder</NuxtLink>
                            </li><!-- /.nav-item -->
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/shop" :class="($nuxt.$route.name === 'shop') ? 'nav__item-link active': 'nav__item-link'">Shop</NuxtLink>
                            </li><!-- /.nav-item -->
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/blogs" :class="($nuxt.$route.name === 'blogs') ? 'nav__item-link active': 'nav__item-link'">Blogs</NuxtLink>
                            </li><!-- /.nav-item -->
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/faqs" :class="($nuxt.$route.name === 'faqs') ? 'nav__item-link active': 'nav__item-link'">Faqs</NuxtLink>
                            </li><!-- /.nav-item -->
                            <li class="nav__item has-dropdown">
                                <NuxtLink to="/contact-us" :class="($nuxt.$route.name === 'contact-us') ? 'nav__item-link active': 'nav__item-link'">Contact Us</NuxtLink>
                            </li><!-- /.nav-item -->
                        </ul><!-- /.navbar-nav -->
                        <button class="close-mobile-menu d-block d-lg-none"><i class="fas fa-times"></i></button>
                    </div><!-- /.navbar-collapse -->
                </div><!-- /.container -->
            </nav><!-- /.navabr -->
        </header><!-- /.Header -->

        <Nuxt />

        <!-- ========================
        Footer
        ========================== -->
        <footer class="footer">
            <div class="footer-primary">
                <div class="container">
                    <div class="row">
                        <div class="col-sm-12 col-md-12 col-lg-4">
                            <div class="footer-widget-about">
                                <img src="/images/logo/logo-light.png" alt="logo" class="mb-30">
                                <p class="color-gray">
                                    Gum and Gums originated from modest beginnings, but our drive and will to achieve
                                    positive change have allowed us to grow into the successful Online Sustainable
                                    Product Store we are today. It’s not just about offering environmentally friendly
                                    and socially responsible products, we strive to inform and inspire the global
                                    community to embrace a sustainable lifestyle.
                                </p>
                            </div><!-- /.footer-widget__content -->
                        </div><!-- /.col-xl-2 -->
                        <div class="col-sm-6 col-md-6 col-lg-2"></div>
                        <div class="col-sm-6 col-md-6 col-lg-2">
                            <div class="footer-widget-nav">
                                <h6 class="footer-widget__title">Links</h6>
                                <nav>
                                    <ul class="list-unstyled">
                                        <li><NuxtLink to="/">Home</NuxtLink></li>
                                        <li><NuxtLink to="/about-us">About Us</NuxtLink></li>
                                        <li><NuxtLink to="/shop">Shop</NuxtLink></li>
                                        <li><NuxtLink to="/blogs">Blogs</NuxtLink></li>
                                        <li><NuxtLink to="/faqs">Faqs</NuxtLink></li>
                                        <li><NuxtLink to="/contact-us">Contact</NuxtLink></li>
                                    </ul>
                                </nav>
                            </div><!-- /.footer-widget__content -->
                        </div><!-- /.col-lg-2 -->
                        <div class="col-sm-12 col-md-6 col-lg-4">
                            <div class="footer-widget-contact">
                                <h6 class="footer-widget__title color-heading">Quick Contacts</h6>
                                <ul class="contact-list list-unstyled">
                                    <li>If you have any questions or need help, feel free to contact with our team.</li>
                                    <li>
                                        <a href="tel:01061245741" class="phone__number">
                                            <i class="icon-phone"></i> <span>+12012904909</span>
                                        </a>
                                    </li>
                                    <li class="color-body">1 Normal Ave. Montclair, NJ 07043</li>
                                </ul>
                                <div class="d-flex align-items-center">
                                    <a href="contact-us.html" class="btn btn__primary btn__link mr-30">
                                        <i class="icon-arrow-right"></i> <span>Get Directions</span>
                                    </a>
                                    <ul class="social-icons list-unstyled mb-0">
                                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                                        <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                                    </ul><!-- /.social-icons -->
                                </div>
                            </div><!-- /.footer-widget__content -->
                        </div><!-- /.col-lg-2 -->
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.footer-primary -->
            <div class="footer-secondary">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-sm-12 col-md-6 col-lg-6">
                            <span class="fz-14">&copy; 2022 Gum and Gums, All Rights Reserved. by</span>
                            <a class="fz-14 color-primary" href="https://www.instagram.com/thesysnetic/">Sysnetic</a>
                        </div><!-- /.col-lg-6 -->
                    </div><!-- /.row -->
                </div><!-- /.container -->
            </div><!-- /.footer-secondary -->
        </footer><!-- /.Footer -->

        <button id="scrollTopBtn"><i class="fas fa-long-arrow-alt-up"></i></button>
    </div>
</template>