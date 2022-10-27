<script setup lang="ts">
import TheSeparator from "~~/components/layout/TheSeparator.vue";

definePageMeta({
  pageTransition: false,
});

useHead({
  title: "marcusn.dev | Learn how to code with Marcus Nilsson.",
  meta: [{
    name: 'description',
    content: "Find articles and step by step guides on how to code fun projects. Become or hire an experienced web developer."
  }]
});

const router = useRouter();

</script>

<template>
  <div class="theme-mode sm:py-12">
    <div class="mx-auto flex min-h-[600px] max-w-7xl justify-center sm:px-6 lg:px-8">

    </div>
    <TheSeparator />
    <div class="bg-primary dark:bg-dprimary">
      <section class="m-auto max-w-screen-lg pt-10 sm:pt-14">
      </section>
    </div>
    <div class="h-10 bg-primary dark:bg-dprimary sm:h-40"></div>
  </div>
</template>
