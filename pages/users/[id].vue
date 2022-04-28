<template>
  <div>
    <p>User ID: {{ $route.params.id }}</p>
    <NuxtLink to="/">Back to Home</NuxtLink>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'main',
});
</script>
