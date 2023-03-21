<template>
  <div class="hero">
    <Header/>
  </div>
</template>

<script>
import Header from "../Header.vue";

export default {
  name: "Hero",
  components: {Header}
}
</script>

<style scoped>
  .hero {
    height: 100vh;
    background-image: url("src/assets/designer.png");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: right;
  }
</style>