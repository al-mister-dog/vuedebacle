<template>
  <div id="app">
    <the-header></the-header>
    <!-- <img src="./assets/tommys-homepage-img.jpg" alt=""> -->
    <home-page></home-page>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import HomePage from './components/HomePage.vue'
export default {
  name: 'App',
  components: {
    TheHeader,
    HomePage
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
  margin-top: 0;
}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  padding: 0;
}

.image {
  height: 10%
}
</style>

