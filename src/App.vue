<script setup lang="ts">
let a = 'a';
console.log(a);
</script>

<template>
  <div>
    vue3 web
    <ol v-for="i in 5">
      <li>{{ i }}</li>
    </ol>
  </div>
</template>

<style scoped></style>
