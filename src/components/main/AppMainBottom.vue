<template>
    <div class="wrapper">
        <div class="container d-flex justify-content-between align-content-center">
            <div class="cards">
                <img src="/images/buy-comics-digital-comics.png" alt="">
                <h5>DIGITAL COMICS</h5>
            </div>
            <div class="cards">
                <img src="/images/buy-comics-merchandise.png" alt="">
                <h5>DC MERCHANDISE</h5>
            </div>
            <div class="cards">
                <img class="locator" src="/images/buy-comics-shop-locator.png" alt="">
                <h5>COMIC SHOP LOCATOR</h5>
            </div>
            <div class="cards">
                <img src="/images/buy-comics-subscriptions.png" alt="">
                <h5>SUBSCRIPTION</h5>
            </div>
            <div class="cards">
                <img src="/images/buy-dc-power-visa.svg" alt="">
                <h5>DC POWER VISA</h5>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;
    .wrapper{
        background-color: $color_primary;
    }
    .cards{
        padding: 60px 0;

        img{
            display: inline-block;
            width: 20%;
        }
        .locator{
            display: inline-block;
            width: 15%;

        }

        h5{
            display: inline-block;
            color: $background_header;
            padding: 0 10px;   
            font-size: 0.8em;
        }

    }

</style>