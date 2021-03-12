<template>
  <div class="teste-for">
    <h1>Teste FOR</h1>
    <ul>
      <li v-for="animal of animais" v-bind:key="animal.id">
        <p>
          <strong>{{ animal.titulo }}</strong>
        </p>
        <img v-bind:src="animal.url" v-bind:alt="animal.nome" />
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "TesteFor",
  data() {
    return {
      animais: [
        {
          id: 1,
          nome: "Gatinho",
          url:
            "https://www.petz.com.br/blog/wp-content/uploads/2020/04/meu-primeiro-gato.jpg",
        },
        {
          id: 2,
          nome: "Cachorrinho",
          url:
            "https://image.cachorrogato.com.br/thumb/1200/630/1/imagens/original/imagem858.jpg",
        },
      ],
    };
  },
};
</script>
<style scoped>
ul {
  display: flex;
  flex-direction: column;
  align-items: center;
}
li {
    list-style: none;
}
img {
    width: 300px;
}
</style>