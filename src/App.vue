<template>
  <div id="app">
    <TesteFor />
  </div>
</template>

<script>
import TesteFor from "./components/TesteFor.vue";

export default {
  name: "App",
  components: {
    TesteFor,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
