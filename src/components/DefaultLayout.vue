<template>
  <navbar />
  <main>
    <div class="max-w-[1200px] x-auto">
      <router-view />
    </div>
  </main>
</template>

<script setup>
import Navbar from '../components/Navbar.vue'
</script>