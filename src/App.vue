<script setup lang="ts">
import NavBar from '@/components/NavBar.vue'
import { RouterView } from 'vue-router'
</script>

<template>
  <NavBar data-theme="light"/>
  <RouterView/>
</template>

<style scoped></style>
