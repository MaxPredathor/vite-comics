<template>
    <div class="wrapper">
        <div class="container d-flex">
            <div class="row my-5">
                <div class="col-12 col-md-4 col-lg-3"
                v-for="comic in comics">
                    <AppCard 
                    :thumb="comic.thumb"
                    :series="comic.series"
                    />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import { comics } from '../../data/comics.js'
import AppCard from './card/AppCard.vue'
    export default {
        name: 'AppMainContent',
        components: {
            AppCard,
        },
        data(){
            return {
                comics: comics
            }
        },
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;
    .wrapper{
        background-color: $background_main;
    }
    h3{
        line-height: 150px;
        font-weight: bold;
    }
</style>