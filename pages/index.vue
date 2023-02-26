<template>
    <div>
        <Slider/>
        <Awards/>
        <About/>
        <Features/>
        <Testimonials/>
    </div>
</template>

<script>
import About from '../components/Home/About.vue';
import Awards from '../components/Home/Awards.vue';
import Slider from '../components/Home/Slider.vue';
import Features from '../components/Home/Features.vue';
import Testimonials from '../components/Home/Testimonials.vue';

export default {
    components: { Slider, Awards, About, Features, Testimonials }
}
</script>