<template>
  <div id="app">
    <Home msg="Home" />
    <About msg="About" />
  </div>
</template>

<script>
import Home from "./components/Home.vue";
import About from "./components/About.vue";

export default {
  name: "App",
  components: {
    Home,
    About,
  },
};
</script>

<style>
#app {
  text-align: center;
  background-color: pink;
  padding: 10% 0;
}
</style>
