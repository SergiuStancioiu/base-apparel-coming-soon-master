<script setup lang="ts">
import HeroMobile from '../assets/images/hero-mobile.jpg';
import HeroDesktop from '../assets/images/hero-desktop.jpg';
</script>

<template>
  <div>
    <img class="md:hidden" :src="HeroMobile" alt="Mobile Img" />
    <img class="hidden md:flex" :src="HeroDesktop" alt="Desktop Img" />
    <div>
      <h1>We're <span>comming soon</span></h1>
      <p>
        Hello fellow shoppers! We're currently building our new fashion store.
        Add your email below to stay up-to-date with announcements and our
        launch deals.
      </p>
    </div>
  </div>
</template>
