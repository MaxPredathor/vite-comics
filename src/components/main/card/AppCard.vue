<template>
    <div class="card">
        <img class="card-img-top" :src="thumb" :alt="series">
        <div class="card-body">
            <p class="card-text">{{ series }}</p>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AppCard',
        props:{
            thumb: String,
            series: String,
        }
        
    }
</script>

<style lang="scss" scoped>
@use '../../../assets/styles/partials/_variables' as *;
    .card{
        width: 300px;
        height: 300px;
        background-color: $background_main;
        border: none;
        margin: 40px 0;
        text-wrap: balance;
        z-index: 99;

        &:hover{
            transform: scale(1.2);
            transition: all 0.2s ease;

            .card-text{
                color: $color_primary;
                font-weight: bold;
            }

        }

        img{
            width: 85%;
            height: 85%;
            object-fit: cover;
            object-position: top;
            border-radius: 0;
        }

        .card-text{
            color: $background_header;
        }
    }

</style>