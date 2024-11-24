<script setup>
import { ref } from "vue";

const counter = ref(0);

function increment() {
  counter.value++;
}
</script>

<template>
  <h1>Home page</h1>
  <p>Counter: {{ counter }}</p>

  <button @click="increment">Click it</button>
</template>
