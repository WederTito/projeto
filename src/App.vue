<template>
<div id="app">
  <div class="header">
     <img src="./assets/img/logo-itpac.png" alt="logo itpac" class="logo">
  <h3 class="title-h">Portal do Administrador</h3>
</div>
</div>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
  <section class="background">

  </section>
<div class="footer">
  <h2 class="text-footer">SIGL - SISTEMA INTEGRADO DE GERENCIAMENTO DE LABORATÓRIOS</h2>
</div>
</template>
<!--
<script>
export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
-->
<style>
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: white;
  margin-top:0;
}
body{
  margin:0;
}
.footer{
  background-color: #e11b22;
  color: white;
  font-family: 'Roboto', 'Times New Roman';
  font-size: 0.7em;
  height: 50px;
}
.text-footer{
  padding-top:1%;
}
#nav {
  padding: 30px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}
#nav a.router-link-exact-active {
  color: #42b983;
}
.header{
  background-color:#f3f3f3;
  display: flexbox;
}
.title-h{
  text-align: right;
  padding: 1%;
  margin:0;
}
.background{
  background-color:#e2e2e2;
  height:500px;
  width:100%;
}
.logo{
  width:10%;
  height:10%;
  align-self: unset;
}
</style>
