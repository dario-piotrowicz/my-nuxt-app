<script setup>
const { data } = await useFetch("/api/test");
console.log({ data });
</script>

<template>
  <div>
    <NuxtWelcome />
  </div>
</template>
