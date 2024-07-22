<script setup>
defineProps(['link', 'icon'])
</script>

<template>
  <a :href="link">
    <img :src="icon" alt="" width="22" height="22" />
  </a>
</template>

<style scoped>
a {
  text-decoration: none;
  transition: transform 0.3s;
}

a:hover {
  transform: scale(1.3);
}
</style>
