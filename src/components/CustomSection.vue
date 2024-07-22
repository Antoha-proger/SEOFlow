<script setup>
defineProps(['section_color', 'section_class'])
</script>

<template>
  <section :class="section_class" :style="{ background_color: section_color }">
    <div class="container">
      <slot></slot>
    </div>
  </section>
</template>
