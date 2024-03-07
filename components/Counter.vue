<script lang="ts" setup>
const count = ref(0);
</script>

<template>
  <div>
    <button @click="count++">Increase</button>
    <span>Count: {{ count }}</span>
    <button @click="count--">Increase</button>
  </div>
</template>
