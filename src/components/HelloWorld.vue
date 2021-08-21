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
  margin: auto;
  padding: 5%;
  border-radius: 20px;
  object-fit: fill;
  background: rgba( 255, 255, 255, 0.25 );
box-shadow: 0 8px 32px 0 rgba(255, 255, 255, 0.37);
backdrop-filter: blur( 41.5px );
-webkit-backdrop-filter: blur( 11.5px );
border-radius: 10px;
border: 1px solid rgba( 255, 255, 255, 0.18 );
}
h1{
  color: #323232
}
</style>
