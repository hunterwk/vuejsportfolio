<template>
  <div id="app">
    <div class="container max-w-3xl mx-auto">
    <img class="mx-auto rounded-lg shadow-md" alt="Vue logo" src="./assets/bitmap.png">
    <br/>
    <HelloWorld msg="Hunter Willoughby Kantner"/>
    </div>
    <AppFooter/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AppFooter
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
