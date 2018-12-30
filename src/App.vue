<template>
  <div id="app">
    <div class="container">
      <img class="rounded-circle img-fluid col-sm-3" src="./assets/logo.png">
      <router-view></router-view>
    </div>
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
  background-color: #2c8fba;
}
html {
  background-color: #2c8fba;
}
</style>
