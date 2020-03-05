<template>
  <div >
 <h2>{{PageName}}</h2>
 <p>{{How}}</p>
 <a :href="Link" target="_blank">More Info</a>
  
  
  </div>
</template>

<script>

export default {
  name: "help",

  data: function(){
    return {

      PageName:  "How sign up with job",
      How: "Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore, culpa. Voluptatem doloremque a fugit voluptate asperiores qui vitae, maxime ut culpa fugiat tempora dignissimos earum magnam illo corporis eaque ipsam delectus exercitationem iusto maiores quisquam optio. Expedita necessitatibus itaque deleniti?",
     Link:"https://vuejs.org/" 
    }
  }

  }

</script>


<style>

</style>