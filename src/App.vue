<script setup>
import { RouterLink, RouterView } from "vue-router";
import LogoSVG from "@/assets/logo.svg?component";
</script>

<template>
  <header>
    <LogoSVG alt="Vite logo" class="logo" />

    <div class="wrapper bg-red-300">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
.logo {
  @apply h-8 w-8;
}
</style>
