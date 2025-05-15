<script setup lang="ts">
useSeoMeta({
  title: "Home",
  meta: [{ name: "description", content: "Home page description" }],
});
</script>

<template>
  <div class="min-h-screen flex flex-col items-center justify-center p-4">
    <h1 class="text-4xl font-bold mb-8 text-center">Nuxt + Tailwind</h1>
    <RouterLink to="/about" class="px-3 py-2 rounded-md text-sm font-medium" active-class="text-primary">Go to About</RouterLink>

    <p class="mt-8 text-muted text-center">Edit pages/index.vue</p>

    <div class="w-full max-w-md mx-auto text-center border-t border-border mt-8 pt-8 text-muted">Powered by RockoAI</div>
  </div>
</template>
