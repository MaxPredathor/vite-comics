<template>
    <header>
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <div class="py-4">
                    <img src="/images/dc-logo.png" alt="DC logo">
                </div>
                <div>
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

        li{
            padding: 50px 10px;
            font-weight: bold;
            color: $nav_list;

            &:hover{
                color: $color_primary;
                border-bottom: 5px solid $color_primary;
                padding: 50px 10px 45px 10px;
            }
        }
    }

</style>