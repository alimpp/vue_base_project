<template>
  <div
    class="home-page d-flex flex-column justify-content-center align-items-center pt-5 px-5 application_animation"
  >
    <h3 class="primary_color size_v_me">{{ $t("message") }}</h3>
    <p class="size_v_s">{{ $t("lorem") }}</p>
  </div>
</template>

<script setup>
import { computed, onMounted } from "vue";
</script>

<style lang="scss" scoped>
.home-page {
  height: 100vh;
}
</style>
