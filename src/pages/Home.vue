<script setup>
import AppLayout from "../components/AppLayout.vue";
</script>

<template>
  <AppLayout imgUrl="/src/assets/img/bg-1.png">
    <div class="wrapper">
      <div class="info">
        <div class="title">Choose your drink</div>
        <div class="line"></div>
      </div>
    </div>
  </AppLayout>
</template>

<style lang="sass" scoped>
@import '../assets/styles/main.sass'

.wrapper
  display: flex
  justify-content: center
  align-items: center

.info
  padding: 80px 0
  text-align: center
</style>
