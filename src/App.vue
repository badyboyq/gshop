<template>
  <div id="app">
    <router-view/>
    <footer-guide v-if="$route.meta.showFooter"> </footer-guide>
  </div>
</template>

<script>
  import  FooterGuide from './components/FooterGuide/FooterGuide.vue'
export default {
  name: 'App',
  components:{FooterGuide}
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale

  color #2c3e50
  width 100%
  height 199%
  background #f5f5f5
  /*margin-top: 60px*/




</style>
