<template>
    <div class="container">
        <Hero/>
        <MainContent/>
        <ProductInfo :text="text" :title="title" imageUrl="src/assets/Lotos.svg"/>
    </div>
</template>

<script>
import Hero from "../components/Home/Hero.vue";
import MainContent from "../components/Home/MainContent.vue";
import ProductInfo from "../components/Home/ProductInfo.vue";

export default {
    name: "Home",
    components: {ProductInfo, MainContent, Hero},
    data() {
        return {
            text: "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus \n" +
                "mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.",
            title: "Light, Fast & Powerful",

        }
    }
}
</script>

<style scoped lang="scss">

</style>