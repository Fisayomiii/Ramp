<template>
    <Hero/>
    <Sectionone/>
    <Sectiontwo />
    <Sectionthree/>
</template>

<script>
import Hero from "../components/component/Hero.vue";
import Sectionone from "../components/component/Sectionone.vue";
import Sectiontwo from "../components/component/Sectiontwo.vue";
import Sectionthree from "../components/component/Sectionthree.vue";

export default {
    components: { Hero, Sectionone, Sectiontwo,Sectionthree },
};
</script>