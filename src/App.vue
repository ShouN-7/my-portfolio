<template>
  <div id="app">
    <img class="circle" src="./assets/logo.png">
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
.circle {
    display: inline-block;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: skyblue;
    text-align:center;
    line-height: 200px;
    vertival-align: middle;
}
</style>
