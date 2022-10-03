<template>
  <div class="hello">
    <h1>Форум</h1>

  </div>
</template>

<script>
import forumData from '@/forumData.json'
console.log(forumData)
export default {
  name: 'HelloWorld'

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
