<template>
    <section>
        <div class="wrapper" :style="{ 'background-image': 'url('+imageUrl+')' }">
            <div class="container">
                <div class="content">
                    <div class="info">
                        <div class="info__title">
                            {{title}}
                        </div>
                        <div class="info__text">
                            <p>{{text}}</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "ProductInfo",
    props: {
        imageUrl: String,
        text: String,
        title: String
    }
}
</script>

<style scoped lang="scss">
.wrapper {
    height: 100vh;
    background-repeat: no-repeat;
    background-size: 50%;
    background-position: left;
}

.container {
    margin: 0 10vw;
}

.content {
    padding: 20% 0;
    width: 35vw;
    float: right;
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
</style>