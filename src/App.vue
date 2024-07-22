<script setup>
import TheHeader from '@/components/Header/TheHeader.vue'
import CustomSection from '@/components/CustomSection.vue'
import BaseButton from '@/components/BaseButton.vue'
</script>

<template>
  <header>
    <div class="container">
      <TheHeader />
    </div>
  </header>

  <main>
    <CustomSection section_class="hero" section_color="#6425cb">
      <div class="left-part">
        <h1 class="hero__title">
          We're strategic <span class="yellow-color">SEO Marketing</span> agency.
        </h1>
        <p class="hero__text">
          Spyro is a powerful landing pages builder WP theme that lets you build high converting
          landing pages using its specially crafted modules clubbed inside.
        </p>
        <BaseButton text="Explore Now" />
      </div>
      <div class="right-part">
        <img
          class="right-part__image"
          src="/src/assets/img/HeroImage.png"
          alt="Главное изображение"
          width="738"
          height="530"
        />
      </div>
    </CustomSection>
  </main>
</template>

<style scoped lang="sass">
header,
.hero
  background-color: #6425cb
  min-height: 162px


.right-part
    &__image
        position: relative
        right: -140px

.hero
    &__title
        font-size: 60px
        max-width: 500px
        color: #fffff
    &__text
</style>
