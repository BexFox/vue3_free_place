<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This is the test web for using @vue3 with babel, webpack, eslint, etc. <br />
    </p>
    <a
      href="https://github.com/BexFox"
      target="_blank"
      rel="noopener">My github url</a>
    <ul>
      <li>
        <a
          href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
          target="_blank"
          rel="noopener">babel</a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
          target="_blank"
          rel="noopener">eslint</a>
      </li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
          rel="noopener">Core Docs</a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
          rel="noopener">Forum</a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
          rel="noopener">Community Chat</a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
          rel="noopener">Twitter</a>
      </li>
      <li>
        <a
          href="https://news.vuejs.org"
          target="_blank"
          rel="noopener">News</a>
      </li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li>
        <a
          href="https://router.vuejs.org"
          target="_blank"
          rel="noopener">vue-router</a>
      </li>
      <li>
        <a
          href="https://vuex.vuejs.org"
          target="_blank"
          rel="noopener">vuex</a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/vue-devtools#vue-devtools"
          target="_blank"
          rel="noopener">vue-devtools</a>
      </li>
      <li>
        <a
          href="https://vue-loader.vuejs.org"
          target="_blank"
          rel="noopener">vue-loader</a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
          rel="noopener">awesome-vue</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'FirstPage',
  props: {
    msg: String
  }
}
</script>

<style scoped>

a {
  color: #42b983;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>