<template>
  <div id="app">
   <Navbar/>
    <router-view />
   <FooterApp/>
  </div>
</template>

<script>
import Navbar from "@/components/inc/Navbar.vue";
import FooterApp from "@/components/inc/FooterApp.vue";
export default {
  name:'app',
  components:{
    Navbar,
    FooterApp
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
