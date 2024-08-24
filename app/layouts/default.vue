<script setup lang="ts">
// ...
</script>

<template>
  <div>
    <!-- <div class="container mx-auto"> -->
    <div
      class="min-h-screen flex flex-col bg-white dark:bg-black animate-wiggle"
    >
      <NavBar class="fixed z-20" />
      <div class="mt-24">
        <main>
          <slot />
        </main>
      </div>
      <TheFooter />
    </div>
    <!-- </div> -->
  </div>
</template>

<style></style>
