<template>
    <main>
        <AppMainJumbo />
        <AppMainContent />
        <AppMainBottom />
    </main>
</template>

<script>
import AppMainContent from './main/AppMainContent.vue'
import AppMainBottom from './main/AppMainBottom.vue'
import AppMainJumbo from './main/AppMainJumbo.vue'
    export default {
        name: 'AppMain',
        components: {
            AppMainContent,
            AppMainBottom,
            AppMainJumbo,
        },
    }
</script>

<style lang="scss" scoped>

</style>