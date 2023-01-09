<template>
    <div>
        <PageTitle pageHeading="About Gum and Gums" pageDesc="Gum & Gums is a Sustainable Oral Hygiene brand that has reinvented the wheel around flossing all of your teeth simultaneously with its premier product Dr. Floss. It is the world’s first one size fits all solution. Enabling ethical sustainability, we aim to achieve this by using Biodegradable materials and Eco-friendly packaging for our products." />
        <About/>
        <Affiliations/>
        <Partners/>
    </div>
</template>

<script>
import Affiliations from '../components/AboutUs/Affiliations.vue';
import Partners from '../components/AboutUs/Partners.vue';
import About from '../components/AboutUs/About.vue'

export default {
    components: { Affiliations, Partners, About }
}
</script>