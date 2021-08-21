<template>
<div class="div">
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Hello, This is me trying VueJS for the first time. 😎"/>
  <Container />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Container from './components/Container.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Container
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
.div{
  background: url("https://i0.wp.com/www.factweavers.com/blog/wp-content/uploads/2018/02/vuejs.png?fit=1120%2C373&ssl=1&resize=1280%2C720") ;
}
HelloWorld{
  color: black
}
</style>
