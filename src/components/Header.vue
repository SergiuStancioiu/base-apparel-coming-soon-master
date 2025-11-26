<script setup lang="ts">
defineProps<{ msg: string }>();
import image from '../assets/vue.svg';
</script>

<template>
  <header>
    <img :src="image" alt="image" />
    <h1>{{ msg }}</h1>
  </header>
</template>
