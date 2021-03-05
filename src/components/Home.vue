<template>
  <div class="container">
    <h1>{{ msg }}</h1>
  </div>
</template>
<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>
<style scoped>
.container{
background-color: orange;
}
</style>