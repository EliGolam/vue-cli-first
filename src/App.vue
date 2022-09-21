<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AppTitle />
    <HeroBG />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue';
import HeroBG from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    AppTitle,
    HeroBG
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
