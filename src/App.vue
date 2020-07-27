<template>
  <div id="app">
    <MyName :name="name" />
  </div>
</template>

<script>
import MyName from './components/MyName'

export default {
  name: 'App',
  components: {
    MyName
  },
  data() {
    return{
      name: 'Abdullahi Odesanmi'
    }
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
