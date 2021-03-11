<template>
  <div id="app">
    <TesteIf />
    <TesteFor />
    <TesteEvento />
    <SitesFavoritos />
  </div>
</template>

<script>
import TesteIf from "./components/TesteIf.vue";
import TesteEvento from "./components/TesteEvento.vue";
import TesteFor from "./components/TesteFor.vue";
import SitesFavoritos from "./components/SitesFavoritos";

export default {
  name: "App",
  components: {
    TesteIf,
    SitesFavoritos,
    TesteFor,
    TesteEvento,
  },
};
</script>


    TesteEvento<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
