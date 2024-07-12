<template>
  <div class="about">
    <h1>Ini {{a}}</h1>
  </div>
</template>

<script setup>
import { ref } from "vue"
let a = 3;

</script>

<style scoped>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
