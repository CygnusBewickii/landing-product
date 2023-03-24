<template>
    <div class="container">
        <Hero/>
        <MainContent/>
        <ProductInfo :text="text" :title="title" imageUrl="src/assets/Lotos.svg"/>
        <ProductInfo :text="text" :title="title" imageUrl="src/assets/social_media.svg"/>
        <ProductInfo :text="text" :title="title" imageUrl="src/assets/bash.svg"/>
        <Price/>
        <Footer/>
    </div>
</template>

<script>
import Hero from "../components/Home/Hero.vue";
import MainContent from "../components/Home/MainContent.vue";
import ProductInfo from "../components/Home/ProductInfo.vue";
import Price from "../components/Home/Price.vue";
import Footer from "../components/Footer.vue";

export default {
    name: "Home",
    components: {Footer, Price, ProductInfo, MainContent, Hero},
    data() {
        return {
            text: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,\n" +
                "molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborumLorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,\n" +
                "molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborumLorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,\n" +
                "molestiae quas vel sint commodi repudiandae consequuntur voluptatum laborum",
            title: "Light, Fast & Powerful",

        }
    }
}
</script>

<style scoped lang="scss">

</style>