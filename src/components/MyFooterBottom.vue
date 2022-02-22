<template>
    <footer>
        <div class="menu-sx">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="menu-dx">
            <a href="#" class="connect-link">
                <img src="../assets/img/footer-facebook.png" alt="">
            </a>
            <a href="#" class="connect-link">
                <img src="../assets/img/footer-periscope.png" alt="">
            </a>
            <a href="#" class="connect-link">
                <img src="../assets/img/footer-pinterest.png" alt="">
            </a>
            <a href="#" class="connect-link">
                <img src="../assets/img/footer-twitter.png" alt="">
            </a>
            <a href="#" class="connect-link">
                <img src="../assets/img/footer-youtube.png" alt="">
            </a>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'MyFooterBottom'
}
</script>

<style scoped lang="scss">

@import "../assets/style/variables.scss";

    footer {
        height: 50px;
        background-color: $bgFooter;
        line-height: 50px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .menu-sx {
            button {
                padding: 10px 15px;
                border: 1px solid blue;
                background-color: $bgFooter;
                color: #fff;
                margin: 0 10px;
                &:hover {
                    cursor: pointer;
                }
            }
        }

        .menu-dx {
            display: flex;
            .connect-link {
                display: flex;
                align-items: center;
                img {
                    width: 20px;
                    height: 20px;
                    padding: 0 10px;
                }
            }
        }
    }

</style>