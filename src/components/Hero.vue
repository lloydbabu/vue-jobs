<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
/**
 * Props for the Hero component.
 * @param title - The title to display in the hero section.
 * @param subtitle - The subtitle to display in the hero section.
 */
defineProps({
  title: {
    type: String,
    default: 'Become a Vue Dev',
  },
  subtitle: {
    type: String,
    default: 'Find the Vue job that fits your skills and needs ',
  },
})
</script>

<template>
  <!-- Hero section component -->
  <section class="bg-green-700 py-20 mb-4">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col items-center">
      <div class="text-center">
        <h1 class="text-4xl font-extrabold text-white sm:text-5xl md:text-6xl">
          {{ title }}
        </h1>
        <p class="my-4 text-xl text-white">{{ subtitle }}</p>
      </div>
    </div>
  </section>
</template>
