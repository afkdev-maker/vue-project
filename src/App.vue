<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyFooter style="text-align:center;position:absolute;bottom:1px;width:50%"></MyFooter>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'app',
  components: {
    HelloWorld, MyFooter
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
