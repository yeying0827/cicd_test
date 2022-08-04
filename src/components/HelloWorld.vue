<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I've learned from Juejin Book
      <a href="https://juejin.cn/book/6897616008173846543" target="_blank" rel="noopener">从 0 到 1 实现一套 CI/CD 流程</a>.
    </p>
    <h3>How to do it?</h3>
    <p>just follow the chapters step by step.</p><!-- 
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul> -->
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
