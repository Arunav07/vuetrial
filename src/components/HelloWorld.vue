<template>
  <div class="navbar">
    <div class="navbarLeft">
      <h1>{{  msg  }}</h1>
    </div>
    <div class="navbarRight">

    </div>
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
.navbar{
  background: url("https://i0.wp.com/www.factweavers.com/blog/wp-content/uploads/2018/02/vuejs.png?fit=1120%2C373&ssl=1&resize=1280%2C720") ;
}
</style>
