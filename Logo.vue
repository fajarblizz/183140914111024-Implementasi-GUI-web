<template>
  <div>
  <img alt="Vue Logo" src="../assets/kalku.png">
  <h1>Created by μ'Fa</h1>
  <h1 class="text-center">Kalkulator Sederhana</h1>
  </div>
</template>

<script>

export default {
  name: 'Logo',
  created () {
    console.log('created')
  },
  mounted () {
    console.log('mounted')
  },
  updated () {
    console.log('updated')
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
</style>
