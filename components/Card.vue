<template>
  <div class="max-w-sm rounded overflow-hidden shadow-lg px-6 py-4 mx-2 bg-gray-800">
    <img class="" :src= image >
    <div class="px-6 py-4">
      <div class="font-bold text-xl mb-2 text-white">{{ title }}</div>
      <p class="text-white text-base">
        Lihat produk selengkapnya disini
      </p>
      <button class="bg-blue-500 hover:bg-blue-700 text-white text-xs font-bold py-2 px-4">
    Pergi
  </button>
    </div>
  </div>
    </template>
  
  <script setup>
  const props = defineProps({
      image: String,
      title: String,
  });
</script>