<template>
  <div class="meu-contador">
    <h1>Meu Contador</h1>
    <p><strong>Contador: {{ contador }}</strong></p>
    <button @click="somarUm">+</button>
    <button @click="removerUm">-</button>
  </div>
</template>

<script>
export default {
    name: 'MeuContador',
    data(){
        return {
            contador: 0
        }
    },
    methods: {
        somarUm(){
            this.contador++;
        },
        removerUm(){
            this.contador--;
        }
    }
}

</script>
