<script setup>
import {ref} from 'vue';
const gustavo = ref('');
const crespo = ref('');
</script>

<template>
   <div>
    <h2><b>First Name</b></h2>
    <br>
    <input v-model="gustavo"  type="text" placeholder="Enter Surname" name="name" >
    <br>
    <h1>{{ gustavo }}</h1>

    <h2><b>Surname</b></h2>
    <br>
    <input v-model="crespo" type="text" placeholder="Enter Surname" name="lastname">
    <br>
    <h1>{{ crespo }}</h1>
   </div>
    

    
</template>

<style scoped>

div{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}


</style>
