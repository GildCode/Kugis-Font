

<template>
  <h1>hola mundo</h1>
 <p>{{contador}}</p> 
  <button @click="increntar"> Increntar</button>
  <button @click="decrementar"> decrementar</button>
</template>

<script setup>
import { ref } from 'vue';
const contador=ref(0);
const increntar=()=>{
  contador.value++
}
const decrementar=()=>{
  contador.value--
}



</script>

<style scoped>
p{
  color:red
}

</style>
