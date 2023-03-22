<template>
    <section class="hero">
        <Header/>
        <div class="info">
            <div class="info__title">
                Introduce Your Product <br>
                Quickly & Effectively
            </div>
            <div class="info__text">
                <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean
                    massa.
                    Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus</p>
                <p>mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis
                    enim.</p>
            </div>
            <div class="info__buttons">
                <router-link to="/store" class="info__link">
                    <div class="info__button info__button-purchase">
                        Purchase UI Kit
                    </div>
                </router-link>
                <router-link to="/learn-more" class="info__link">
                    <div class="info__button info__button-learn-more">
                        Learn More
                    </div>
                </router-link>
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
    background-image: url("src/assets/designer.svg");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: right;
}

.info {
    margin-left: 10vw;
    margin-top: 15vh;
    width: 35vw;
    .info__title {
        font-size: 50px;
        color: #091133;
        font-weight: 500;
        margin-bottom: 25px;
        line-height: 66px;
    }

    .info__text {
        font-size: 18px;
        color: #505F98;
        margin-bottom: 40px;
        line-height: 30px;
        p {
            margin-bottom: 20px;
        }

        p:last-child {
            margin-bottom: 0;
        }
    }
    .info__link {
        text-decoration: none;
    }
    .info__buttons {
        display: flex;
        .info__button {
            display: flex;
            width: 190px;
            height: 36px;
            justify-content: center;
            align-items: center;
            text-decoration: none;
            margin-right: 30px;
            border-radius: 2px;
            font-weight: 500;
            font-size: 16px;
        }
        .info__button-purchase {
            background-color: #111B47;
            color: white;
            &:hover {
                background-color: #314c91;
                transition-duration: 0.5s;
            }
        }
        .info__button-learn-more {
            height: 30px;
            border: 3px solid #091133;
            color: black;
            &:hover {
                background-color: #111B47;
                color: white;
                transition-duration: 0.5s;
            }
        }
    }
}
</style>