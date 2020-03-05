<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
      <p>I really like vue 🎈🎈</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.hello{
  height: 100vh;
  display:flex;
  align-items: center;
  justify-content:center;
  flex-direction: column;
  background:#444;
  color: #3c78b4;

}

</style>
