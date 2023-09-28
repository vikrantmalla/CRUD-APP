<script setup>
import { ref } from "vue";
const count = ref(0);
</script>

<template>
  <div>
    <h3>This current count is...</h3>
    <h1>{{ count }}</h1>
    <div>
      <button @click="count++">+</button>
      <button @click="count--">-</button>
    </div>
  </div>
</template>