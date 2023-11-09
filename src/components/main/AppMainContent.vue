<template>
    <div class="wrapper">
        <div class="container d-flex">
            <h3 class="text-light">--&gt; Content goes here &lt;--</h3>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AppMainContent'
    }
</script>

<style lang="scss" scoped>
@use '../../assets/styles/partials/_variables' as *;
    .wrapper{
        background-color: $background_main;
        height: 150px;
    }
    h3{
        line-height: 150px;
        font-weight: bold;
    }

</style>