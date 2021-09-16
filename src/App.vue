<template>
  <div id="app">
    <HelloWorld msg="Show me the money"/>
    <MyFooter style="position:absolute;bottom:1px;width:100%"></MyFooter>
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
