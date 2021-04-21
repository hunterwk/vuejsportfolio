<template>
  <div id="app">
    <div class="container max-w-3xl mx-auto">
    <img class="mx-auto rounded-lg shadow-md" alt="Vue logo" src="./assets/bitmap.png">
    <br/>
    <HelloWorld msg="Hunter Willoughby Kantner"/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/footer.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Footer
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
