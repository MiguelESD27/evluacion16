<template>
  <div id="app">
    <NavBar></NavBar>
    <router-view/>
  </div>
</template>
<script>
import NavBar from '@/components/NavBar.vue'
export default {
  components:{
    NavBar
  }
}
</script>
<style>
@import "https://use.fontawesome.com/releases/v5.2.0/css/all.css";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
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
</style>
