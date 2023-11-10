<template>
    <div class="wrapper">
        <div class="container d-flex justify-content-between">
            <div>
                <button class="btn">SING-UP NOW!</button>
            </div>
            <div class="d-flex justify-content-evenly">
                <h4>FOLLOW US</h4>
                <div>
                    <img src="/images/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="/images/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="/images/footer-youtube.png" alt="">
                </div>
                <div>
                    <img src="/images/footer-periscope.png" alt="">
                </div>
                <div>
                    <img src="/images/footer-pinterest.png" alt="">
                </div>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'AppFooterSignUp'
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;

    .wrapper{
        background-color: $background_footer;
    }
    h4{
        color: $color_primary;
        font-weight: bold;
        padding: 30px 10px;
    }
    img{
        padding: 30px 10px;
    }
    button{
        color: $background_header;
        font-weight: bold;
        border: 2px solid $color_primary;
        border-radius: 0;
        margin-top: 30px;

        &:hover{
            border: 2px solid $color_primary;
            color: $color_primary;
            transform: scale(1.2);
            transition: all 0.3s ease;
            text-decoration: underline;
        }
        
    }


</style>