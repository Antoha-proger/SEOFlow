<script setup>
defineProps(['section_color', 'section_class'])
</script>

<template>
  <section :class="section_class" :style="{ 'background-color': section_color }">
    <div :class="['container', `${section_class}__container`]">
      <slot></slot>
    </div>
  </section>
</template>
