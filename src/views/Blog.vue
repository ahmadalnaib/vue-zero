<template>
  <div class="blog">
    <h2 class="bg-danger">{{PageName}}</h2>
<div class="container">
  <div class="row">
    <div class="col-md-8">
      <div class="posts">
      <BlogPosts/>
      </div>
    </div>
    <div class="col-md-4">
      <div class="sidebar">
        <BlogSidebar/>
      </div>
    </div>
  </div>
</div>
  </div>
</template>


<script>
import BlogPosts from "@/components/Blog/BlogPosts.vue";
import BlogSidebar from "@/components/Blog/BlogSidebar.vue";

export default {
  name:"blog",
  components:{
    BlogPosts,
    BlogSidebar
  },
  
  data: function(){
    return{
      PageName:"Welcome to Blog Page ",

    }
  }

}
</script>


<style scoped>

</style>