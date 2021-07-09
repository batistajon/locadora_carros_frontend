<template>
  <div id="app">
    <nav-bar />
    <div id="form" class="row justify-content-md-center">
      <div class="col-md-auto">
        <login />
      </div>
    </div>
  </div>
</template>

<script>
import Login from './components/Login.vue';
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    Login,
    NavBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#form {
  margin-top: 60px;
}
</style>
