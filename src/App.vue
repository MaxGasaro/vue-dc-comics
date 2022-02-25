<template>
  <div id="app">
    <MyHeader/>
    <MyJumbotron/>
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
import MyJumbotron from './components/partials/MyJumbotron.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
    MyFooterBottom,
    MyJumbotron
  }
}
</script>

<style lang="scss">
#app {
  /*@import "./assets/style/general.scss";*/
}
</style>
