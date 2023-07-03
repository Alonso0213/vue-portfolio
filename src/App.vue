<template>
  <div>
    <navBar/>
    <fubar/>
  <router-view/>
  
   
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
nav {
  padding: 30px;
  
}

nav a {
  font-weight: bold;
  color: #ffffff;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #f01515;
}
</style>
<script>
import navBar from './components/navBar.vue'
import Footer from './components/fubar.vue'
export default{
  components:{
    navBar,
    Footer
   
  }
}


</script>
