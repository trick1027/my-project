<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
     <h2 class="primary">git merge 내가 먼저 sksss</h2>
    <ul>
      <li><i class="ico_com level_h">level h</i></li>
    </ul>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel 이것도</p>
    <p class="level_v">evel v</p>
    <p class="level_v">evel v</p>
    <p class="level_v">이것도 바꿔봐</p>
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
