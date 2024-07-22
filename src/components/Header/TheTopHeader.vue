<script setup>
import ContactLink from '@/components/Links/ContactLink.vue'
import SocialMediaLink from '@/components/Links/SocialMediaLink.vue'
</script>

<template>
  <div class="top-header container">
    <div class="contact-links__block">
      <ContactLink icon="/src/assets/icons/PhoneIcon.svg" text="+1800-123-4567" link="#" />
      <ContactLink
        icon="/src/assets/icons/TelegramIcon.svg"
        text="info@brandexponents.com"
        link="#"
      />
    </div>

    <div class="social-links__block">
      <SocialMediaLink icon="/src/assets/icons/Facebook.svg" link="#" />
      <SocialMediaLink icon="/src/assets/icons/Twiter.svg" link="#" />
      <SocialMediaLink icon="/src/assets/icons/In.svg" link="#" />
      <SocialMediaLink icon="/src/assets/icons/Pinterest.svg" link="#" />
    </div>
  </div>
</template>

<style scoped>
.top-header {
  display: flex;
  justify-content: space-between;
  padding: 20px 0;
}
.contact-links__block {
  display: flex;
  column-gap: 20px;
}

.social-links__block {
  display: flex;
  column-gap: 10px;
}
</style>
