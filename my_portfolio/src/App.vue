<script setup>
import { RouterView } from 'vue-router';
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
  <HeaderComponent />
  <main>
    <RouterView />
  </main>
  <FooterComponent />
</template>

<style scoped>
main {
  padding: 2rem;
}
</style>

