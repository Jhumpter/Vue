<template>
    <div>
        <input v-model="mensagem"/>
        <p>Mensagem: <strong>{{ mensagem }}</strong></p>
    </div>
</template>

<style>
</style>

<script setup>
import { ref } from 'vue'
//ref cria uma variável reativa, acessado por mensagem.value no script, mas no template é só mensagem
//o v-model liga o input à variável
const mensagem = ref('E aí?')
</script>