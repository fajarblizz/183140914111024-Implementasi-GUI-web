<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/kalku.png">
    <HelloWorld :pesan="message"/>
    <!-- <input v-model="message" placeholder="edit me"> -->
    <!-- /*v-bind:id="message"*/ -->
  </div>
</template>

<script>
import HelloWorld from './components/Kalkulator.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data () {
    return ({
      message: 'Kalkulator Sederhana'
    })
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
  background-color: rgb(0, 0, 0);
}
</style>
