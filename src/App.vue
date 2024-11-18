<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <TheExperience />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import TheExperience from './components/TheExperience'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    TheExperience
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
  margin-top: 60px;
}
</style>
