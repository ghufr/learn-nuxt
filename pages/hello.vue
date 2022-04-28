<template>
  <div>
    <h1>Hello Page</h1>
    <NuxtLink to="/">Home Page</NuxtLink>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'main',
});
const route = useRoute();
</script>

<style></style>
