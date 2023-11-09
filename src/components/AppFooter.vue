<template>
    <AppFooterDc />
    <AppFooterSignUp />
</template>

<script>
import AppFooterDc from './footer/AppFooterDc.vue'
import AppFooterSignUp from './footer/AppFooterSignUp.vue'
    export default {
        name: 'AppFooter',
        components: {
            AppFooterDc,
            AppFooterSignUp
        },
    }
</script>

<style lang="scss" scoped>

</style>