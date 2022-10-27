<script setup lang="ts">
import TheSeparator from "./TheSeparator.vue";
</script>

<template>
  <div class="mobile-menu relative h-full w-[100%]">
    <div
      class="mobile-menu absolute z-[100] h-[100vh] w-full bg-accent text-white dark:bg-daccent"
    >
      <div class="p-5 font-bold">
        <ul>
          <NuxtLink to="/">
            <li class="p-2 underline underline-offset-8">Home</li>
          </NuxtLink>
        </ul>
      </div>
      <TheSeparator></TheSeparator>
      <div class="h-full bg-primary p-5 dark:bg-dprimary">
      </div>
    </div>
  </div>
</template>
