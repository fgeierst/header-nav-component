<script setup>
import MucNavigation from './MucNavigation.vue';

defineProps({
  logo: String,
})

</script>

<template>
  <header>
    <div>{{ logo }}</div>
    <MucNavigation msg="This is the Navigation" />
  </header>
</template>

<style scoped>

</style>
