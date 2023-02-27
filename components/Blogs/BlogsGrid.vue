<template>
    <!-- ======================
        Blog Grid
    ========================= -->
    <section class="blog-grid">
        <div class="container">
            <div class="row">
                <Blog blogImage="/images/blog/grid/1.jpeg" blogTitle="Meet the Summer 2022 E-Team Cohort!" blogDesc="We are excited to announce the 17 early-stage student innovator teams that have been accepted into our Summer 2022 E-Team Grant Program! Teams were chosen based on the potential for their innovation to have a significant positive social, health, or environmental impact."  blogLink="/blogs/blog1" />
                <Blog blogImage="/images/blog/grid/2.jpeg" blogTitle="Hate flossing? Felicano Center’s pitch contest winners may have solution" blogDesc="The Feliciano Center for Entrepreneurship & Innovation at Montclair State University announced the student winners of its annual Startup Montclair Pitch Competition, which was held virtually this year due to the COVID-19 pandemic." blogLink="/blogs/blog2" />
                <Blog blogImage="/images/blog/grid/3.jpeg" blogTitle="Pitch Contest Transforms Dreams Into Reality." blogDesc="A biology major and a mathematics major win Feliciano Center for Entrepreneurship & Innovation’s Startup Montclair Pitch Competition." blogLink="/blogs/blog3" />
            </div><!-- /.row -->
            <div class="row">
                <div class="col-12 text-center">
                    <nav class="pagination-area">
                        <ul class="pagination justify-content-center">
                            <li><a class="current" href="#">1</a></li>
                            <li><a href="#" style="pointer-events: none;"><i class="icon-arrow-right"></i></a></li>
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
