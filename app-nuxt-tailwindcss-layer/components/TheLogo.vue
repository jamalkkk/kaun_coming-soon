<script setup lang="ts">
import site from '~~/site'

const { name, logo } = site
</script>

<template>
  <NuxtLink data-pg-name="Logo" class="flex items-center sm:flex-row" to="/">
    <div class="w-12 h-12">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 206.9 206.9">
        <defs></defs>
        <g id="Layer_2" data-name="Layer 2">
          <g id="Layer_1-2" data-name="Layer 1">
            <path
              class="cls-1"
              style="fill: #fff"
              d="M176.6,30.3Q146.3,0,103.45,0T30.3,30.3Q0,60.6,0,103.45T30.3,176.6q30.3,30.3,73.15,30.3t73.15-30.3q30.3-30.3,30.3-73.15T176.6,30.3ZM142,106.7a78.11,78.11,0,0,1-5.9,26.15q-4.8,11.51-11.8,16.1a24.83,24.83,0,0,1-12.2,4,35.31,35.31,0,0,1-13-1.6,105.16,105.16,0,0,1-14.35-6.1q-4.2-2.1-5.65-2.9a47.18,47.18,0,0,1-5.4-3.45,35.57,35.57,0,0,1-9.4-10.9,41.73,41.73,0,0,1-4.8-13.65Q57.1,100.65,62.7,85.75A45.11,45.11,0,0,1,69.2,73.6a26.34,26.34,0,0,1,10.4-8.4,31.35,31.35,0,0,1,12.9-2.1q1.75,0,13.35,1.15c1.47.17,3.63.38,6.5.65a34.48,34.48,0,0,1,6.35,1.3,25.81,25.81,0,0,1,9.1,5.15,25.53,25.53,0,0,1,6.35,8.4c.33.73.8,1.9,1.4,3.5s1,2.73,1.4,3.5.92,1.83,1.85,3.6a39.7,39.7,0,0,1,1.7,3.6Q142.41,98.85,142,106.7Z"
            />
          </g>
        </g>
      </svg>
    </div>
    <h6
      class="text-primary-600 dark:text-primary-200 font-extrabold font-serif ml-2 mt-4 text-2xl"
    >
      {{ name }}
    </h6>
  </NuxtLink>
</template>

<style scoped></style>
