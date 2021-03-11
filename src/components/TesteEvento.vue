<template>
  <div class="teste-evento">
    <h1>{{ mensagem }}</h1>
    <button v-on:click="deixarMaiuscula">Texto em Maiúsculo</button>
    <button v-on:click="deixarMinuscula">Texto em Minúsculo</button>
  </div>
</template>
<script>
export default {
  name: "TesteEvento",
  data() {
    return {
      mensagem: "o rato roeu a roupa do rei de roma",
    };
  },
  methods: {
    deixarMaiuscula() {
      this.mensagem = this.mensagem.toUpperCase();
    },
    deixarMinuscula() {
        this.mensagem = this.mensagem.toLowerCase();
    },
  },
};
</script>


<style scoped>
</style>