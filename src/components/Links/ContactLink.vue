<script setup>
defineProps(['link', 'icon', 'text'])
</script>

<template>
  <a class="contact-link" :href="link">
    <img :src="icon" alt="" width="28" height="28" />
    <p>{{ text }}</p>
  </a>
</template>

<style scoped>
.contact-link {
  display: flex;
  align-items: center;
  column-gap: 12px;
  text-decoration: none;
  color: #fff;
  transition: color 0.3s;
}

.contact-link:hover {
  color: var(--base-yellow-color);
}

p {
  font-size: 15px;
}
</style>
