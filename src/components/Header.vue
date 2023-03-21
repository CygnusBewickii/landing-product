<template>
  <header>
    <div class="navigation-panel">
      <nav>
        <span class="navigation-panel__item">Home</span>
        <span class="navigation-panel__item">About</span>
        <span class="navigation-panel__item">Contact</span>
      </nav>
    </div>
    <div class="title">
      Landing
    </div>
    <div class="button-wrapper">
      <div class="buy-button">
        <span>Buy now</span>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped lang="scss">
  header {
    display: flex;
    justify-content: space-evenly;
    height: 60px;
    padding: 15px 0;
  }
  .navigation-panel {
    width: 245px;
    nav {
      display: flex;
      justify-content: space-between;
      .navigation-panel__item {
        font-family: 'Roboto';
        font-weight: 400;
        font-size: 14px;
        color: #505F98;
      }
    }
  }
  .title {
    font-family: 'Roboto';
    font-weight: 900;
    font-size: 26px;
    color: #37447E;
  }
  .button-wrapper {
    width: 245px;
    display: flex;
    justify-content: end;
  }
  .buy-button {
    width: 160px;
    height: 26px;
    border-radius: 2px;
    background: #111B47;
    text-align: center;
    span {
      color: white;
      vertical-align: middle;
      font-weight: 500;
      font-size: 12px;
      padding-top: 7px;
    }
  }
</style>