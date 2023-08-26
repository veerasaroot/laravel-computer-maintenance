<script setup>
import { containerMaxW } from "@/Config.js";
</script>

<template>
  <section class="p-6" :class="containerMaxW">
    <slot />
  </section>
</template>
