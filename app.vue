<template>
  <NuxtWelcome />
</template>

<script setup>
const count = ref(0);

const greet = () => {
  console.log(count)
}

const increment = () => {
  count.value++;
}
</script>

<style lang="scss">
body {
  background-color: var(--surface-0);
  font-family: var(--font-family);
  font-weight: 400;
  color: var(--text-color);
  margin: 0;
  padding: 0;
}
</style>