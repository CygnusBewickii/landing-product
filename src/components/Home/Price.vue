<template>
    <section>
        <div class="wrapper">
            <div class="content">
                <div class="title">
                    A Price To Suit Everyone
                </div>
                <div class="text">
                    Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean
                    massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus
                </div>
                <div class="price">
                        <div class="price__value">
                            $40
                        </div>
                        <div class="price__description">
                            UI Design Kit
                        </div>
                </div>
                <div class="purchase">
                    <div class="purchase__description">
                        See, One price. Simple.
                    </div>
                    <router-link to="/store">
                        <div class="purchase__button">
                            Purchase Now
                        </div>
                    </router-link>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Price"
}
</script>

<style scoped lang="scss">
section {
    height: 100vh;
    background-image: url("src/assets/price_background.svg");
    background-size: cover;
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        .content {
            width: 33.3%;
            margin-top: 10%;
            text-align: center;
            .title {
                font-weight: 500;
                font-size: 36px;
                line-height: 48px;
                color: #091133;
                margin-bottom: 16px;
            }
            .text {
                max-width: 600px;
                font-size: 16px;
                line-height: 26px;
                color: #6F7CB2;
                margin-bottom: 36px;
            }
            .price {
                margin-bottom: 50px;
                .price__value {
                    font-weight: 500;
                    font-size: 50px;
                    line-height: 66px;
                    letter-spacing: 1px;
                    color: #222F65;
                }
                .price__description {
                    margin-top: 5px;
                }
            }
            .purchase {
                .purchase__description {
                    font-size: 14px;
                    color: #5D6970;
                    margin-bottom: 10px;
                }
                .purchase__button {
                    width: 190px;
                    margin: 0 auto;
                    font-weight: 500;
                    font-size: 14px;
                    background-color: #111B47;
                    color: white;
                    padding: 10px 0;
                    border-radius: 2px;
                }
            }
        }
    }

}
</style>