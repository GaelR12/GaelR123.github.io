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

<!-- so why does nothing show up when i load in my .io ones i deployed i have commited files but it does not show up in the pages
 -->
