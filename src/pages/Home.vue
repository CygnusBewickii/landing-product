<template>
    <div class="container">
        <Hero/>
        <MainContent/>
    </div>
</template>

<script>
import Hero from "../components/Home/Hero.vue";
import MainContent from "../components/Home/MainContent.vue";

export default {
    name: "Home",
    components: {MainContent, Hero}
}
</script>

<style scoped lang="scss">

</style>