<template>
  <div class="min-h-screen flex flex-col">
    <Navbar />
    <main class="flex-1 p-4">
      <Dashboard />
    </main>
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Dashboard from './components/Dashboard.vue';
import Footer from './components/Footer.vue';
</script>