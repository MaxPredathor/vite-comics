<template>
    <main>
        <AppMainContent />
        <AppMainBottom />
    </main>
</template>

<script>
import AppMainContent from './main/AppMainContent.vue'
import AppMainBottom from './main/AppMainBottom.vue'
    export default {
        name: 'AppMain',
        components: {
            AppMainContent,
            AppMainBottom,
        }
    }
</script>

<style lang="scss" scoped>

</style>