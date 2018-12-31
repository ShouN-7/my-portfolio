<template>
  <div id="app">
    <div class="container">
      <div class="alert-primary mb-3 col-sm-3 mx-auto rounded balloon">
        <p class="h2">{{ message }}</p>
      </div>
      <img class="rounded-circle img-fluid col-sm-3" src="./assets/logo.png">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      message: 'Hello, Im ShouN'
    }
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
  background-color: #2c8fba;
}
html {
  background-color: #2c8fba;
}
.balloon {
  margin: 1.5em 0;
  pading: 7px 10px;
  min-width: 120px;
  color: #555;
  font-size: 16px;
  background: #e0edff;
}

.balloon:before{
  content: "";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -15px;
  border: 15px solid transparent;
  border-top: 15px solid #e0edff;
}

.balloon p {
  margin: 0;
  padding: 0;
}
</style>
