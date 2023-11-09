<template>
  <AppHeader />
  <AppMain />
  <MyAppFooter />
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import MyAppFooter from './components/MyAppFooter.vue'
  export default {
    name: 'App',
    components: {
      AppHeader,
      AppMain,
      MyAppFooter
    },
    data(){
      return{

      }

    },
  }
</script>

<style lang="scss" scoped>

</style>