<template>
    <!-- ======================
        Blog Grid
    ========================= -->
    <section class="blog-grid">
        <div class="container">
            <div class="row">
                <Blog blogImage="/images/blog/grid/1.jpeg" blogTitle="Hate flossing? Felicano Center’s pitch contest winners may have solution" blogDesc="The Feliciano Center for Entrepreneurship & Innovation at Montclair State University announced the student winners of its annual Startup Montclair Pitch Competition, which was held virtually this year due to the COVID-19 pandemic." blogLink="#" />
                <Blog blogImage="/images/blog/grid/2.jpeg" blogTitle="Pitch Contest Transforms Dreams Into Reality" blogDesc="Proving that ingenuity can be found in every corner of the Montclair State community amid even the most difficult circumstances, two non-business majors have won this year’s student portion of the Feliciano Center for Entrepreneurship & Innovation’s annual Startup." blogLink="#" />
                <Blog blogImage="/images/blog/grid/3.jpeg" blogTitle="Biology and Math Students Take First Place in Feliciano Pitch Contest" blogDesc="Junior biology major Hassan Kashif and freshman mathematics major Zaki Tahir created Dr. Floss, a one-time-use, eco-friendly device that enables buyers to floss all of their teeth simultaneously." blogLink="#" />
            </div><!-- /.row -->
            <div class="row">
                <div class="col-12 text-center">
                    <nav class="pagination-area">
                        <ul class="pagination justify-content-center">
                            <li><a class="current" href="#">1</a></li>
                            <li><a href="#">2</a></li>
                            <li><a href="#"><i class="icon-arrow-right"></i></a></li>
                        </ul>
                    </nav><!-- .pagination-area -->
                </div><!-- /.col-12 -->
            </div><!-- /.row -->
        </div><!-- /.container -->
    </section><!-- /.blog Grid -->
</template>

<script>
import Blog from './Blog.vue'

export default {
    components: { Blog }
}
</script>