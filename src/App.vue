
<template>
<div class="div">
  <span class="material-icons">
toggle_on
</span>
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
  background: #390352;
  box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
backdrop-filter: blur( 11.5px );
-webkit-backdrop-filter: blur( 11.5px );
border-radius: 10px;
border: 1px solid #6c0080 0.25;
}
.div.black{
    background: #000000;
  box-shadow: 0 8px 32px 0 rgba(32, 32, 39, 0.37);
backdrop-filter: blur( 11.5px );
-webkit-backdrop-filter: blur( 11.5px );
border-radius: 10px;
border: 1px solid #2f2f2f 0.25;
}
HelloWorld{
  color: black
}
.material-icons{
  color: #Ffffff;
  width: 40px;
  height: 20px;
}
</style>
