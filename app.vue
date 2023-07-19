<script setup>
const { data } = useFetch("/api/test");
</script>

<template>
  <div>
    <div>Below content is rendered from the backend:</div>
    <div>{{ data }}</div>
  </div>
</template>
