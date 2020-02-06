<template>
  <div>
  <form  class="text-center" style="margin-top: 5%">
        <h1 class="text-center">Penjumlahan</h1>
        <input type="number" v-model.number="angka_1">
        <h1 class="text-center"> + </h1>
        <input type="number" v-model.number="angka_2">
    </form>
  <h2 class="text-center">{{ angka_1 + angka_2}}</h2>
  </div>
</template>

<script>

export default {
  name: 'Penambahan',
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
<script>
export default { data: function () {
  return { angka_1: null, angka_2: null, angka_3: null, angka_4: null, angka_5: null, angka_6: null, angka_7: null, angka_8: null
  }
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
