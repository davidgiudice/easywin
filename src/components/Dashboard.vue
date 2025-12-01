<template>
  <div class="bg-white rounded-lg shadow p-6">
    <h2 class="text-2xl font-bold mb-4">Place Your Bets</h2>
    <BetForm />
    <BetList />
  </div>
</template>

<script setup>
import BetForm from './BetForm.vue';
import BetList from './BetList.vue';
</script>