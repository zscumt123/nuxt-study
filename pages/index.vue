<template>
  <div>
    <h1>index</h1>
    <div>{{ data?.api }}</div>
  </div>
</template>
<script setup lang="ts"> 
  const { data } = await useFetch('/api/hello')
</script>
