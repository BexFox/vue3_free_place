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
</style>