<template>
  <div id="app">
    <cvDo />
  </div>
</template>

<script>
import cvDo from "./components/cvDo.vue";
export default {
  name: "App",
  components: {
    cvDo,
  },
};
</script>

<style>
@import url("./style/reset.css");
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap");
#app {
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
