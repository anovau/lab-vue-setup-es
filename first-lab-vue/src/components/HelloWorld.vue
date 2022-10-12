<template>
  <h1>{{ message }}</h1>
  <button @click="helloworld" >Press me</button>
  
</template>

<script setup>
import { ref } from "vue";
let message = ref("Hello World");

const helloworld = () => {
  console.log("Hello World!");
  message.value = "Boton Activado"
}
</script>
>
<style scoped>

</style>
