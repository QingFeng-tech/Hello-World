<template>
  <div id="app">
    <img src="./assets/logo.png">
	<HelloWorld msg="欢迎来到菜鸟教程"></HelloWorld>
  </div>
</template>

<script>
	import HelloWorld from "./components/HelloWorld.vue"
export default {
  name: 'App',
  components:{
	  HelloWorld
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
