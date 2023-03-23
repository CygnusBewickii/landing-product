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
                    <div class="purchase__button">
                        Purchase Now
                    </div>
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
    background-image: url("src/assets/Rectangle.png");
    background-size: cover;
    .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        .content {
            width: 33.3%;
            margin-top: 15%;
            .title {
                font-weight: 500;
                font-size: 36px;
                line-height: 48px;
                color: #091133;
                text-align: center;
                margin-bottom: 16px;
            }
            .text {
                text-align: center;
                max-width: 600px;
                font-size: 16px;
                line-height: 26px;
                color: #6F7CB2;
                margin-bottom: 36px;
            }
            .price {
                text-align: center;
                .price__value {
                    font-weight: 500;
                    font-size: 50px;
                    line-height: 66px;
                    letter-spacing: 1px;
                    color: #222F65;
                }
                .price__description {
                    margin-top: 10px;
                }
            }
        }
    }

}
</style>