<template>
    <header>
        <div class="navigation-panel">
            <nav>
                <router-link to="/" class="navigation-panel__link"><span class="navigation-panel__item">Home</span>
                </router-link>
                <router-link to="/about" class="navigation-panel__link"><span
                    class="navigation-panel__item">About</span></router-link>
                <router-link to="/contacts" class="navigation-panel__link"><span
                    class="navigation-panel__item">Contact</span></router-link>
            </nav>
        </div>
        <div class="title">
            Landing
        </div>
        <div class="button-wrapper">
            <router-link to="/store" class="buy-button">
                <span>Buy now</span>
            </router-link>
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
    justify-content: space-between;
    height: 60px;
    margin: 0 10vw;
    padding: 15px 0;
}

.navigation-panel {
    width: 245px;

    nav {
        display: flex;
        justify-content: space-between;

        .navigation-panel__item {
            font-size: 14px;
            color: #505F98;
        }

        .navigation-panel__link {
            text-decoration: none;
        }
    }
}

.title {
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
    text-decoration: none;

    span {
        color: white;
        vertical-align: middle;
        font-weight: 500;
        font-size: 12px;
        padding-top: 7px;
    }
}
</style>