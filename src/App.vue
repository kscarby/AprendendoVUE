<template>
  <div id="app">
    <MeuContador />
    <TesteIf />
    <TesteFor />
    <TesteEvento />
    <SitesFavoritos />
  </div>
</template>

<script>
import MeuContador from "./components/MeuContador"
import TesteIf from "./components/TesteIf";
import TesteEvento from "./components/TesteEvento";
import TesteFor from "./components/TesteFor";
import SitesFavoritos from "./components/SitesFavoritos";

export default {
  name: "App",
  components: {
    MeuContador,
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
