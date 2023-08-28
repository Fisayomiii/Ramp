<template>
    <Hero/>
    <Sectionone/>
    <!-- <Sectiontwo /> -->
</template>

<script>
import Hero from "../components/component/Hero.vue";
import Sectionone from "../components/component/Sectionone.vue";
import Sectiontwo from "../components/component/Sectiontwo.vue";
export default {
    components: { Hero, Sectionone, Sectiontwo },
};
</script>