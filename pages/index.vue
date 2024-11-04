<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <div>
    <h1>Page: 首頁</h1>
    <div>
      目前路由的路徑 - route.fullPath 為: {{ route.fullPath }}
    </div>
  </div>
</template>

<style scoped></style>
