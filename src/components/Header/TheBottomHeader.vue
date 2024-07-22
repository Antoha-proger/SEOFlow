<script setup>
import MainMenu from '@/components/MainMenu.vue'
import BaseButton from '@/components/BaseButton.vue'
</script>

<template>
  <div class="bottom-header container">
    <img src="/src/assets/icons/Logo.svg" alt="Лого" width="94" height="17" />
    <MainMenu />
    <BaseButton text="Enquiry" />
  </div>
</template>

<style scoped>
.bottom-header {
  width: 100%;
  background-color: #fff;
  border-radius: 10px;
  padding: 30px 15px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
