<template>
  <div class="about">
    <h1>{{PageName}}</h1>
    <P>{{AboutAhmed}}</P>
  
  </div>
</template>

<script>


export default {
  name: "about",
  data:function(){
    return {

      PageName:"About page",
      AboutAhmed:"Ahmed is webdevloper he work with laravel php and vue "
    }
  }
};
</script>
