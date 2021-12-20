<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
<<<<<<< HEAD
     <h2 class="primary">git merge merge</h2>
=======
     <h2 class="primary">git merge</h2>
>>>>>>> 2ab157141d90d7b51ffd2cd8567aeb3d670e9853
    <ul>
      <li><i class="ico_com level_h">level h</i></li>
    </ul>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
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
