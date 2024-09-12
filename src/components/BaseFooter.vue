<template>
  <section class="footer"></section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.footer {
  background-image: url(/img/Vector2.png);
  background-repeat: no-repeat;
  background-size: 100% 100%; /* Полное растягивание по ширине и высоте */
  background-position: center;
  min-height: 370px;
  @media (max-width: 400px) {
    min-height: 230px;
  }
}
</style>
