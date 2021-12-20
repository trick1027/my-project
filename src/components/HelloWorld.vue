<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
<<<<<<< HEAD
     <h2 class="primary">git merge 나중거</h2>
=======
     <h2 class="primary">git merge 이걸로</h2>
>>>>>>> bbb35fb514a1599610a5e50fe3cb214b6cf31771
    <ul>
      <li><i class="ico_com level_h">level h</i></li>
    </ul>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel TEST</p>
    <ul>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
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
