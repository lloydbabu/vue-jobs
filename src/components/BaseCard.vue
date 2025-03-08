<script setup lang="ts">
/**
 * Props for the BaseCard component.
 * @param bg - The background color class for the card.
 */
defineProps({
  bg: {
    type: String,
    default: 'bg-gray-100'
  }
});
</script>
<template>
  <!-- Base card component -->
  <div :class="`${bg} p-6 rounded-lg shadow-md`">
    <slot></slot>
  </div>
</template>
