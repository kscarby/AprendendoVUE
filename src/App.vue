<template>
  <div id="app">
    <TesteIf/>
    <TesteFor/>
    <TesteEvento/>
  </div>
</template>

<script>
import TesteIf from './components/TesteIf.vue';
import TesteEvento from './components/TesteEvento.vue';
import TesteFor from "./components/TesteFor.vue";

export default {
  name: "App",
  components: {
    TesteIf,
    TesteFor,TesteEvento,
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
