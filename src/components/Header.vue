<script setup>
import Logo from "@/assets/logo.svg"
</script>

<template>
  <header>
    <img :src="Logo" alt="VueJS Logo" />
    <h1>Hi, I'm <span class="highlight">Vue</span></h1>
  </header>
</template>

<style scoped>
img {
  height: 150px;
}
h1 {
  font-size: 2rem;
  color: #34495e;
  margin-top: 10px;
}
</style>
