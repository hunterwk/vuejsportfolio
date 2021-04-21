<template>
  <div class="hello">
    <div class="border-b-8">
    <h1>{{ msg }}</h1>
    <span>Full Stack Web Developer and Hospitality Veteran.</span>
    </div>
    <div class="flex">
      <div class="mx-auto flex"> 
    <a href="https://github.com/hunterwk" target="_blank"
      ><img class="icon" src="../assets/github.svg" alt="github icon"
    /></a>
    <a href="https://www.linkedin.com/in/hunter-kantner-780788194/" target="_blank"
      ><img class="icon" src="../assets/linkedin.svg" alt="linkedin icon"
    /></a>
    <a href="mailto:hunterkantner@gmail.com" target="_blank"
      ><img class="icon" src="../assets/gmail.svg" alt="email icon"
    /></a>
    </div>
    </div>
    <h3>About me</h3>
    <About/>

    <h3>Prior Work</h3>
    <PastWork/>
    <h3>TIL</h3>
    <TIL/>
    <ul></ul>
  </div>
</template>

<script>
import About from './about.vue'
import PastWork from './PastWork.vue'
import TIL from './TIL.vue'



export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  components: {
    About,
    PastWork,
    TIL
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 3rem;
}
h3 {
  margin: 20px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.icon {
  height: 60px;
  width: 60px;
  margin: 10px 10px 10px;
}
</style>
