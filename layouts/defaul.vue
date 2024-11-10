<template>
    <div>
      <Header /> <!-- Your custom header component -->
      <NuxtLayout>
        <NuxtPage />
      </NuxtLayout>
    </div>
  </template>
  
  <script setup>
  import Header from '~/components/Header.vue';
  </script>
  