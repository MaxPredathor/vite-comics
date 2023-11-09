<template>
    <header>
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <div class="py-3">
                    <img src="/images/dc-logo.png" alt="DC logo">
                </div>
                <div class="my-div">
                    <ul class="d-flex justify-content-between">
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li>TV</li>
                        <li>GAMES</li>
                        <li>COLLECTIBLES</li>
                        <li>VIDEO</li>
                        <li>FANS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
                </div>
            </div>
        </div>       
    </header>
</template>

<script>
    export default {
        name: 'AppHeader'
        
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/_variables' as *;
    header{
        background-color: $background_header;
    }
    ul{
        list-style: none;
        height: 100%;
        margin: 0 !important;

        li{
            padding: 60px 10px;
            font-weight: bold;
            color: $nav_list;
            height: 100%;

            &:hover{
                color: $color_primary;
                border-bottom: 5px solid $color_primary;
                padding: 60px 10px 55px 10px;
            }
        }
        .my-div{
            height: 100%;
            
        }
    }

</style>