<template>
    <div>
        <Slider/>
        <About/>
        <Features/>
        <Team/>
    </div>
</template>

<script>
import About from '../components/Home/About.vue';
import Slider from '../components/Home/Slider.vue';
import Features from '../components/Home/Features.vue';
import Team from '../components/Home/Team.vue';

export default {
    components: { Slider, About, Features, Team }
}
</script>