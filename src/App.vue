<template>
  <div class="bg-gray-100 h-full">
    <header class="bg-white shadow h-16 flex justify-between items-stretch">
      <RouterLink :to="{name: 'home'}" class="inline-flex items-center px-5">
        Home
      </RouterLink>
      <div class="flex items-center gap-1">
        <RouterLink to='/' class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">Search Meals</RouterLink>
        <RouterLink to='/' class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">Meals By Letter</RouterLink>
        <RouterLink to='/' class="inline-flex items-center px-2 h-full transition-colors hover:bg-purple-100">Meals By Ingredients</RouterLink>
      </div>
    </header>
    <main>
      <RouterView />
    </main>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>
