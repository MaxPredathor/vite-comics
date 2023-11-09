<template>
    <div class="wrapper">
        <div class="container d-flex justify-content-between">
            <div class="d-flex">
                <div>
                    <div>
                        <ul>
                            <h3>DC COMICS</h3>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div>
                        <ul>
                            <h3>SHOP</h3>
                            <li>Shop DC</li>
                            <li>Shop DC Collactibles</li>
                        </ul>
                    </div>              
                </div>
                <div>
                    <ul>
                        <h3>DC</h3>
                        <li>Terms of Use</li>
                        <li>Priuvacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    <ul>
                        <h3>SITES</h3>
                        <li>DC</li>
                        <li>MAD Magazines</li>
                        <li>DC Kids</li>
                        <li>DC universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <div>
                <img class=" img-fluid" src="/images/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AppFooterDc',
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;
    .wrapper{
        background-image: url(/images/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height: 400px;
        overflow: hidden;
    }
    ul{
        list-style: none;
        margin: 40px 0;

        li{
            color: $footer_li;
            font-size: 0.8em;
        }
    }

    h3{
            color: $background_header;
            font-weight: bold;
        }
    .img-fluid{
        position: relative;
        top: -100px;
        height: 600px;

    }
</style>