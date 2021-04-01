<template>
  <div id="app">
    <HelloWorld/>
    <Jumbotron/>
    <Footer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Jumbotron
  }
}
</script>

<style>
html {
  padding: 0;
  margin: 0;
}
* {
  padding: 0;
  margin: 0;
}
</style>
