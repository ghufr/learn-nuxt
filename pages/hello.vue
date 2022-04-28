<template>
  <div class="max-w-5xl mx-auto">
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
