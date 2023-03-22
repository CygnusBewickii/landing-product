<template>
  <section class="hero">
    <Header/>
    <div class="info">
        <div class="info__title">
            Introduce Your Product <br>
            Quickly & Effectively
        </div>
        <div class="info__text">
            <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa.
                Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus</p>
            <p>mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.</p>
        </div>
        <div class="info__buttons">

        </div>
    </div>
  </section>
</template>

<script>
import Header from "../Header.vue";

export default {
  name: "Hero",
  components: {Header}
}
</script>

<style scoped lang="scss">
  .hero {
    height: 100vh;
    background-image: url("src/assets/designer.png");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: right;
  }
  .info {
      margin-left: 15.5vw;
      margin-top: 15vh;
      width: 35vw;
      .info__title {
          font-size: 50px;
          color: #091133;
          font-weight: 500;
          margin-bottom: 20px;
      }
      .info__text {
          font-size: 18px;
          color: #505F98;
      }
  }
</style>