<script setup>
defineProps(['text'])
</script>

<template>
  <button class="base-button">{{ text }}</button>
</template>

<style scoped>
.base-button {
  background-color: var(--base-yellow-color);
  color: #fff;
  padding: 11px 26px;
  border: 1px solid var(--base-yellow-color);
  border-radius: 30px;
  cursor: pointer;
  transition: all 0.3s;
}

.base-button:hover {
  background-color: #fff;
  color: var(--base-yellow-color);
}
</style>
