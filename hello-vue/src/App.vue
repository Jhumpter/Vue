<script setup>
import meuComponente from './components/Meucomponente.vue'
import Vmodel from './components/Vmodel.vue';
</script>

<template>
  <div class="main">
    <meuComponente/>
    <Vmodel/>
  </div>
  
</template>

<style>
.main {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
</style>