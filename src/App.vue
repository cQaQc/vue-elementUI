<template>
  <div id="app">
    <img src="./assets/logo.png">

    <router-view></router-view>
    <router-link to="/main">页面一</router-link>
    <router-link to="/login">页面二</router-link>
    <router-view></router-view>
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
