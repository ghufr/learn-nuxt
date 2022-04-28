<template>
  <div>
    <div class="bg-gray-100">
      <div class="max-w-5xl mx-auto">
        <header class="flex justify-between py-4 shadow-sm">
          <h1 class="font-bold text-lg">Acme Corp</h1>
          <ul class="flex font-semibold">
            <li>
              <NuxtLink to="/" class="p-3">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/about" class="p-3">About</NuxtLink>
            </li>
          </ul>
        </header>
      </div>
    </div>

    <div>
      <slot />
    </div>
    <footer class="bg-gray-200 py-2">
      <div class="max-w-5xl mx-auto">
        <p class="text-center">This is footer</p>
      </div>
    </footer>
  </div>
</template>
