<template>
    <section>
        <div class="wrapper">
            <div class="container">
                <div class="content">
                    <div class="info">
                        <div class="info__title">
                            Light, Fast & Powerful
                        </div>
                        <div class="info__text">
                            <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
                                dolor.
                                Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur
                                ridiculus</p>
                            <p>mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla
                                consequat
                                massa quis enim.</p>
                        </div>
                    </div>
                    <div class="features">
                        <div class="features__block">
                            <div class="features__image">
                                <img src="src/assets/Icon.svg" alt="">
                            </div>
                            <div class="features__title">
                                Title Goes Here
                            </div>
                            <div class="features__text">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet animi dicta dignissimos
                                dolores eveniet excepturi harum, hic itaque laudantium necessitatibus neque nostrum
                                placeat praesentium quisquam recusandae veniam, vitae? Deleniti, sint!
                            </div>
                        </div>
                        <div class="features__block">
                            <div class="features__image">
                                <img src="src/assets/Icon.svg" alt="">
                            </div>
                            <div class="features__title">
                                Title Goes Here
                            </div>
                            <div class="features__text">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet animi dicta dignissimos
                                dolores eveniet excepturi harum, hic itaque laudantium necessitatibus neque nostrum
                                placeat praesentium quisquam recusandae veniam, vitae? Deleniti, sint!
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "MainContent"
}
</script>

<style scoped lang="scss">
.wrapper {
    height: 100vh;
    background-image: url("src/assets/girl_with_mobile.svg");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: right;
}

.container {
    margin: 0 10vw;
}

.content {
    padding: 20% 0;
    width: 35vw;
}

.info {
    margin-bottom: 40px;

    .info__title {
        font-weight: 500;
        font-size: 36px;
        color: #091133;
        margin-bottom: 30px;
    }

    .info__text {
        font-size: 16px;
        color: #6F7CB2;
        line-height: 26px;
        p {
            margin-bottom: 15px;

            &:last-child {
                margin-bottom: 0;
            }
        }
    }
}

.features {
    display: grid;
    flex-direction: row;
    grid-template-columns: 46% 46%;
    gap: 8%;

    .features__image {
        margin-bottom: 10px;
    }
    .features__title {
        font-weight: 500;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .features__text {
        font-size: 12px;
        line-height: 18px;
        color: #5D6970;
    }
}
</style>