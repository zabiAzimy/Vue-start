<template>
  <HelloWorld msg="Welcome to learning Vue.js"/>
  <img alt="Vue logo" src="./assets/logo.png">
  <PAGES />
  <Inputboxes />
  <hr>
  <ShowHide />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PAGES from './components/new_onef.vue'
import Inputboxes from './components/inputboxes.vue';
import ShowHide from './components/show_hide.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PAGES,
    Inputboxes,
    ShowHide
}
}
</script>

<style>
body{
  background-color: #001D4A;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(22, 165, 58);
  margin-top: 60px;
}
</style>
