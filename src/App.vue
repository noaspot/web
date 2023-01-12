<template>
  <Landing/>
</template>

<script>
import Landing from './components/Landing.vue'

export default {
  name: 'App',
  components: {
    Landing
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;900&display=swap");

body {
  background: linear-gradient(to right top, #F2D685, #F37335);
    background-attachment: fixed;
}

#app {
  font-family: "Montserrat", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 50px;
}
</style>
