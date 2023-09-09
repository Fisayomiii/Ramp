<template>
    <Hero />
    <Sectionone />
    <Sectiontwo />
    <Sectionthree />
    <Sectionfour />
    <Sectionfive />
</template>

<script>
import Hero from "../components/component/Hero.vue";
import Sectionone from "../components/component/Sectionone.vue";
import Sectiontwo from "../components/component/Sectiontwo.vue";
import Sectionthree from "../components/component/Sectionthree.vue";
import Sectionfour from "../components/component/Sectionfour.vue";
import Sectionfive from "../components/component/Sectionfive.vue";

export default {
    components: { Hero, Sectionone, Sectiontwo, Sectionthree, Sectionfour, Sectionfive },
};
</script>