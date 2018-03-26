<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      我是框架的模板层，比如footer,header这些都可以写在这里
    </div>
    <div class="">
      <router-link to="page">跳到page</router-link>
      <router-link to="home">跳到home</router-link>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
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
