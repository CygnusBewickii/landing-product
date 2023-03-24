<template>
    <footer>
        <div class="container">
            <div class="main-block">
                <div class="copyright">
                    ©2023 Yourcompany
                </div>
                <div class="title">
                    Landing
                </div>
                <router-link to="/store">
                    <div class="purchase-button">
                        Purchase now
                    </div>
                </router-link>
            </div>
            <div class="lower-block">
                <nav class="pages">
                    <router-link to="/Home" class="pages__link">
                        <div class="pages__item">Home</div>
                    </router-link>
                    <router-link to="/About" class="pages__link">
                        <div class="pages__item">About</div>
                    </router-link>
                    <router-link to="/Contacts" class="pages__link">
                        <div class="pages__item">
                            Contact
                        </div>
                    </router-link>
                </nav>
                <nav class="social-media">
                    <div class="social-media__item">
                        <a href="#">
                            <img src="src/assets/facebook.svg" alt="">
                        </a>
                    </div>
                    <div class="social-media__item">
                        <a href="#">
                            <img src="src/assets/linked_in.svg" alt="">
                        </a>
                    </div>
                    <div class="social-media__item">
                        <a href="#">
                            <img src="src/assets/Twitter_icon.svg" alt="">
                        </a>
                    </div>
                    <div class="social-media__item">
                        <a href="#">
                            <img src="src/assets/youtube_logo.svg" alt="">
                        </a>
                    </div>
                    <div class="social-media__item">
                        <a href="#">
                            <img src="src/assets/Instagram_icon.svg" alt="">
                        </a>
                    </div>
                </nav>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped lang="scss">
    .container {
        margin: 0 10vw;
    }
    footer {
        height: 216px;
        background-color: #E7ECFF;
        .main-block {
            display: flex;
            justify-content: space-between;
            padding-top: 65px;
            .copyright {
                font-weight: 500;
                font-size: 14px;
                color: #939EA4;
            }
            .title {
                font-weight: 900;
                font-size: 26px;
                color: #37447E;
            }
            .purchase-button {
                width: 190px;
                background-color: #111B47;
                color: white;
                font-weight: 500;
                font-size: 12px;
                padding: 10px 0;
                text-align: center;
            }
        }
        .lower-block {
            border-top: 1px solid #CDD1D4;
            margin-top: 20px;
            padding-top: 20px;
            display: flex;
            justify-content: space-between;
            .pages {
                display: flex;
                justify-content: space-between;
                width: 250px;
                .pages__link {
                    text-decoration: none;
                    font-size: 14px;
                    color: #929ECC;
                }
            }
            .social-media {
                display: flex;
                justify-content: space-between;
                width: 250px;
            }
            
        }
    }
</style>