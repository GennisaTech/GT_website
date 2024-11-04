<script setup lang="ts">
import { RouterView } from 'vue-router'
import PageLayout from './components/PageLayout/PageLayout.vue'
import './public.scss'
</script>

<template>
  <PageLayout>
    <RouterView />
  </PageLayout>
</template>

<style scoped></style>
