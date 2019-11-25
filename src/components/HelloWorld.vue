<template>
  <div class="hello">
    <h2>{{ msg1 }}</h2>
    <h1>{{ msg2 }}</h1>
    <h3>{{ msg3 }}</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg1: 'Welcome to My World',
      msg2: 'Meng-lin Hsieh Protfolio',
      msg3: '個人網站架設測試成功',
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
