<script setup>
import { ref, computed } from 'vue'
const cidades = ['São Paulo','Rio de Janeiro','Belo Horizonte','Salvador','Fortaleza','Curitiba','Manaus','Recife','Porto Alegre','Brasília']

</script>

<template>
<ul>
  <li v-for="(cidade, index) in cidades.sort()" :key="index">{{ cidade }}</li>
</ul>
</template>

<style scoped>
</style>
