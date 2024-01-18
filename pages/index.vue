<template>Hello from pages {{ data?.hello }}</template>

<script setup lang="ts">
  const { data } = await useFetch('/api/hello');
</script>
