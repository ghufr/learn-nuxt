<template>
  <div class="max-w-5xl mx-auto">
    isOpen: {{ open }}
    <br />
    <button @click="open = true">Open Modal</button>
    <Teleport to="body">
      <div v-if="open" class="modal">
        <p>Hello from the modal!</p>
        <button @click="open = false">Close</button>
      </div>
    </Teleport>
  </div>
</template>

<script setup>
definePageMeta({
  layout: 'main',
});
const open = useState('open', () => false);
</script>
