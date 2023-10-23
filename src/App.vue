<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>

  <div class="main">
    <RouterView />
  </div>

</template>

<style scoped>

@keyframes slideInLeft {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}

* {
  animation: 1s ease-out 0s 1 slideInLeft;
  margin: 0;
  padding: 0;
  user-select: none;
}
</style>
