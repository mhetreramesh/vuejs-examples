<template>
  <span v-bind:title="msg">
    Hover your mouse over me for a few seconds
    to see my dynamically bound title!
  </span>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'You loaded this page on ' + new Date().toLocaleString()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
