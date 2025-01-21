<script setup lang="ts">
defineProps<{
  author: string;
  description: string;
}>();
</script>

<template>
  <div class="border border-4 border-y-0 border-gray-700">
    <div class="bg-black h-8 flex justify-between px-4">
      <h1 class="text-white">{{ author }}</h1>

      <p class="text-white cursor-pointer">x</p>
    </div>
    <div class="py-6 px-4 bg-gray-900">
      <p class="text-white text-3xl">
        {{ description }}
      </p>
    </div>
  </div>
</template>
