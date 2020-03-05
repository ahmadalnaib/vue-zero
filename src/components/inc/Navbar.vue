<template>
  <div class="navbar">
    <div class="menu-btn">
      <i class="fas fa-bars fa-2x"></i>
    </div>
    <h4 class="logo">AhmedHabeeb</h4>
     <ul id="nav">
      <router-link to="/" tag="li" exact>
      <a>Home</a>
      </router-link> |
      <router-link to="/about" tag="li">
      <a>About</a>
      </router-link> |
      <router-link to="/blog" tag="li">
      <a>Blog</a>
      </router-link> |
      <router-link to="/help" tag="li" >
      <a>Help</a>
      </router-link>
    </ul>

  </div>
</template>

<script>
export default {
  name:"Navbar"
}
</script>


<style scoped>



a{
  
  padding:20px;
  text-decoration: none
}

.navbar {
  display:flex;
  justify-content: space-around;
  align-items: center;
  margin:10px;

}

#nav {
  display:flex;
  flex-direction:row;
  padding:20px;
  margin:10px;
  
}

ul{
  list-style: none;
}


@media (max-width:500px) {
#nav{
  flex-direction: column;
}
  
}
</style>