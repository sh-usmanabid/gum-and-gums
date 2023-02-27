<template>
    <!-- ========================= 
        Testimonials
    =========================  -->
    <section class="testimonials-layout2 pt-130 pb-130">
      <div class="container">
        <div class="testimonials-wrapper">
          <div class="row">
            <div class="col-sm-12 col-md-12 col-lg-5">
              <div class="heading-layout2">
                <h3 class="heading__title">Hear From Experts</h3>
                <p>Here's what the dentists have to say about Dr. Floss</p>
              </div><!-- /.heading -->
            </div><!-- /.col-lg-5 -->
            <div class="col-sm-12 col-md-12 col-lg-7">
              <carousel class="testimonial-slider" :loop="true" :margin=30 :nav="false" :dots="false" :smartSpeed=300 :autoplay="false" :responsive="res">
                <!-- Testimonial #1 -->
                <div class="testimonial-item item-1">
                  <h3 class="testimonial__title">“Flossing is difficult for most patients.  DR. FLOSS is a great alternative for those patients that have a hard time time using regular string floss.  Being that you "floss" all teeth at once, there is little to no bacteria transfer from site to site in comparison to traditional dental picks.  And it's definitely alot less time consuming.”</h3>
                    <div>
                        <div class="testimonial__thumb">
                            <img src="/images/team/1.jpg" alt="author thumb">
                        </div>
                        <div>
                            <h4 class="testimonial__meta-title">Dr. Zakia Anjum Akhtar</h4>
                            <p class="testimonial__meta-desc">DDS (NYU), Residency (St. Vincent's Medical Center)</p>
                        </div>
                    </div>
                </div><!-- /. testimonial-item -->
                <!-- Testimonial #2 -->
                <div class="testimonial-item item-2">
                  <h3 class="testimonial__title">“Dr. Floss will indeed be a revolutionary replacement of conventional flossing, its unique and innovative design will be a choice for those who want quick and easy way to maintain their oral hygiene.”
                  </h3>
                    <div class="testimonial__thumb">
                        <img src="/images/team/2.jpg" alt="author thumb">
                    </div>
                    <div>
                        <h4 class="testimonial__meta-title">Dr. Rashid Mahmood</h4>
                        <p class="testimonial__meta-desc">DBDS Dental Surgeon & Orthodontist</p>
                    </div>
                </div><!-- /. testimonial-item -->
              </carousel><!-- /.slick-carousel -->
            </div><!-- /.col-lg-7 -->
          </div><!-- /.row -->
        </div><!-- /.testimonials-wrapper -->
      </div><!-- /.container -->
    </section><!-- /.testimonials layout 2 -->
</template>

<script>
export default {
    data() {
        return {
          res: {
            0: {
                items: 1
            },
            480: {
                items: 1
            },
            600: {
                items: 1
            },
            800: {
                items: 1
            },
            1024: {
                items: 1
            }
          }
        }
    }
}
</script>

<style scoped>
.testimonial__thumb img {
  height: 100px !important;
  width: 100px !important;
  border-radius: 50%;
  margin-bottom: 10px;
}
</style>