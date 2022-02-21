<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyFooter/>
    <MyFooterBottom/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyMain from './components/MyMain.vue';
import MyFooter from './components/MyFooter.vue';
import MyFooterBottom from './components/MyFooterBottom.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
    MyFooterBottom
  }
}
</script>

<style lang="scss">
#app {
 
}
</style>
