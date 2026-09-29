<script setup>
import { useCounter } from "@/composables/useCounter";

const { count, increment, decrement, reset } = useCounter();
</script>

<template>
  <div class="card bg-base-100 border-base-300 border shadow-sm">
    <div class="card-body items-center text-center">
      <h2 class="card-title">Counter Demo</h2>
      <p class="my-3 text-5xl font-semibold">{{ count }}</p>
      <div class="flex justify-center gap-2">
        <button class="btn btn-outline btn-neutral" @click="decrement">−</button>
        <button class="btn btn-primary" @click="increment">+</button>
        <button class="btn btn-outline btn-error" @click="reset">Reset</button>
      </div>
      <p class="text-base-content/60 mt-3 text-sm">Count is persisted to IndexedDB with Dexie.</p>
    </div>
  </div>
</template>
