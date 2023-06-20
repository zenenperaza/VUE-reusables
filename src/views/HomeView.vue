<template>
<MainLayout>
  <template v-slot:main>
    MAIN SLOT
  </template>
  <template v-slot:aux>
    AUX SLOT
  </template>
</MainLayout>
</template>

<script lang="ts" setup>
   import MainLayout from '@/layouts/MainLayout.vue'
</script>

<style scoped>
</style>
