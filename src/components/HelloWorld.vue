<template>
    <div class="hello">
    <p>Hello 大家好，我是小浩</p>

    <p>很高兴你来到这里</p>


    <ul>
      <li> <a href="http://bikan8.cn">必看吧</a> </li>
      <li> <a href="http://bikan8.cn">bikan8.cn</a> </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
