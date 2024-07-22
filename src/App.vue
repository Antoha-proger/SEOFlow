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
    <section class="hero">
      <div class="hero__container container">
        <div class="hero__left-part">
          <h1 class="hero__title">
            We're strategic <span class="yellow-color">SEO Marketing</span> agency.
          </h1>
          <p class="hero__text">
            Spyro is a powerful landing pages builder WP theme that lets you build high converting
            landing pages using its specially crafted modules clubbed inside.
          </p>
          <BaseButton text="Explore Now" />
        </div>
        <div class="hero__right-part">
          <img
            class="hero__image"
            src="/src/assets/img/HeroImage.png"
            alt="Главное изображение"
            width="738"
            height="530"
          />
        </div>
      </div>
    </section>
  </main>
</template>

<style scoped lang="sass">
header
  background-color: #6425cb
  min-height: 162px

.hero
  background-color: #6425cb

  &__container
    display: flex
    // column-gap: 20px
    padding: 75px 0
    align-items: center

  &__right-part
    width: 60%

  &__left-part
    width: 40%

  &__image
    position: relative
    right: -40px

  &__title
    font-size: 60px
    max-width: 650px
    color: #FFFFFF
    margin-bottom: 35px

  &__text
    color: #FFFFFF
    max-width: 400px
    line-height: 34px
    margin-bottom: 25px
</style>
