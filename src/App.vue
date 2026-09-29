<template>
  <nav class="border-base-300 bg-base-200 border-b">
    <div class="navbar mx-auto max-w-5xl px-4">
      <div class="flex-1">
        <RouterLink class="text-lg font-semibold" to="/">Vue Boilerplate</RouterLink>
      </div>
      <div class="flex gap-1">
        <RouterLink class="nav-link btn btn-ghost" to="/">Home</RouterLink>
        <RouterLink class="nav-link btn btn-ghost" to="/about">About</RouterLink>
      </div>
    </div>
  </nav>
  <main class="mx-auto max-w-5xl px-4 py-8">
    <RouterView />
  </main>
</template>
