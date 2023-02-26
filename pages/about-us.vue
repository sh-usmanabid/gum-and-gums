<template>
    <div>
        <PageTitle pageHeading="About The Founder" />
        <About/>
        <Affiliations/>
        <Partners/>
    </div>
</template>

<script>
import Affiliations from '../components/AboutUs/Affiliations.vue';
import Partners from '../components/AboutUs/Partners.vue';
import About from '../components/AboutUs/About.vue';

export default {
    components: { Affiliations, Partners, About }
}
</script>