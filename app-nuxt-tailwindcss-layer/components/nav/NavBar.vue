<script setup lang="ts">
const { navlinks, navlinksPrimary, navlinksSecondary, currentPath } = useNav()
</script>

<template>
  <div class="w-full">
    <nav class>
      <div class="container mx-auto px-4 sm:px-6">
        <div class="flex h-24 items-center justify-between">
          <div class="flex items-center justify-between w-full">
            <div class="flex flex-shrink-0 items-center">
              <TheLogo />
            </div>
          </div>
          <DarkModeSwitch />
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped></style>
