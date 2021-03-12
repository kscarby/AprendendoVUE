<template>
  <div class="teste-if">
    <h1 v-if="podeVer">Agora vc pode me ver!</h1>
    <h1 v-else>Vc não pode me ver!</h1>
  </div>
</template>

<script>
export default {
  name: "TesteIf",

  data() {
    return {
      podeVer: false,
    };
  },
};
</script>

<style scoped>
</style>