<template>
  <div id="app">
    <Logo/>
    <penambahan/>
    <HelloWorld :pesan="message"/>
    <!-- <input v-model="message" placeholder="edit me"> -->
    <!-- /*v-bind:id="message"*/ -->
    <Calculator/>
    </div>
</template>

<script>
import HelloWorld from './components/Kalkulator.vue'
import Logo from './components/Logo.vue'
import Penambahan from './components/Penambahan.vue'
import Calculator from './components/Calculator.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Logo,
    Penambahan,
    Calculator
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
  color: #ffd700;
  margin-top: 60px;
  background-color: rgb(0, 0, 0);
}
</style>
