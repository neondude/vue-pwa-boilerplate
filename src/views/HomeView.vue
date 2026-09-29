<script setup>
import DemoCounter from "@/components/DemoCounter.vue";
</script>

<template>
  <div class="mx-auto max-w-2xl">
      <h1 class="mb-2 text-3xl font-bold">Vue 3 Boilerplate</h1>
      <p class="text-base-content/60 mb-6">A starter template with Vue 3, Vue Router, DaisyUI, Tailwind CSS, PWA support, and Vitest.</p>

      <DemoCounter class="mb-6" />

      <div class="card bg-base-100 border-base-300 border shadow-sm">
        <div class="card-body">
          <h2 class="card-title">Patterns in this template</h2>
          <ul class="ml-5 list-disc space-y-2">
            <li><strong>Dexie + IndexedDB persistence</strong> — reactive counter state survives page reloads and browser restarts</li>
            <li><strong>Lazy-loaded routes</strong> — <code>AboutView</code> is loaded on demand via dynamic <code>import()</code></li>
            <li><strong>DaisyUI + Tailwind CSS</strong> — component classes and utilities are generated through the Vite plugin</li>
          </ul>
        </div>
      </div>
  </div>
</template>
