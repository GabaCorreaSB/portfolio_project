<template>
  <HeaderPage />
  <div class="hello">
    <h1>Hello I'm Gaba</h1>
    <p> I'm a software engineer currently working at the finance industry</p>
  </div>
</template>

<script>
import HeaderPage from './HeaderPage.vue'
export default {
  name: 'HomePage',
  components:{
    HeaderPage
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
