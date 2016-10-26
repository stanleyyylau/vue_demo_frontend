<template>
  <div id="app">
    <login></login>
    <todoitem v-bind:myprop = "testprop"></todoitem>
  </div>
</template>

<script>
import login from './login.vue'
import todoitem from './todoitem.vue'
export default {
  components: {
    login,
    todoitem
  },
  data () {
    return {
      msg: 'I dont know what this is...',
      ads: 'Vue is fucking awesome, see we got this community....',
      testprop: 'fjiwegjirjwijijrigj'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

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
