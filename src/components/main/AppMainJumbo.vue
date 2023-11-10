<template>
    <div class="wrapper">
        <button>CURRENT SERIES</button>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;
    .wrapper{
        background-image: url(/images/jumbotron.jpg);
        background-size: cover;
        height: 400px;
        position: relative;
    }
    button{
        background-color: $color_primary;
        color: $background_header;
        font-weight: bold;
        font-size: 1.2em;
        border: none;
        padding: 10px 20px;
        position: absolute;
        bottom: -25px;
        left: 15%;

        &:hover{
            transform: scale(1.2);

        }
    }

</style>