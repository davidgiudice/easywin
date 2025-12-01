<template>
  <div>
    <h3 class="text-lg font-semibold mb-2">Active Bets</h3>
    <ul class="list-disc pl-5">
      <li v-for="bet in bets" :key="bet.id" class="mb-2">
        <span class="font-medium">{{ bet.description }}</span> - ${{ bet.amount }}
      </li>
    </ul>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const bets = ref([
  { id: 1, description: 'Bet 1', amount: 50 },
  { id: 2, description: 'Bet 2', amount: 100 },
]);
</script>