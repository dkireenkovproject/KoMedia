<template>
  <section class="content">
    <div class="container">
      <div class="content__wrapper">
        <div class="content__content"><img src="/img/img3.png" alt="photo" /></div>
        <div class="content__sidebar">
          <ul class="list-reset content__list">
            <li class="content__item">Фото</li>
            <li class="content__item">Видео</li>
            <li class="content__item">Рилс</li>
            <li class="content__item">Трансляции</li>
          </ul>
          <div class="content__text">
            <span class="content__span">Больше наших работ </span>
            <a href="https://t.me/KOmediatg" target="_blank" class="content__link">Смотреть</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.content {
  padding-bottom: 40px;
  border-top: 1px solid #000;
  border-bottom: 1px solid #000;
  @media (max-width: 930px) {
    display: none;
  }
  &__wrapper {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 80px;
  }
  &__list {
    display: flex;
    flex-direction: column;
    margin-bottom: 60px;
    gap: 80px;
    background-size: cover;
    padding: 50px 20px;
    text-align: center;
    color: #fff;
    position: relative;
    width: 200px;
    height: 630px;
    background-image: url(/img/content.png);
  }
  &__item {
    color: rgba(255, 255, 255, 0.55);
    font-family: 'Inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
  }
  &__content {
    padding-top: 50px;
  }
  &__sidebar {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  &__text {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  &__span {
    color: rgba(255, 255, 255, 0.7);
    font-family: 'Inter';
    font-size: 24px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 28.8px */
  }
  &__link {
    padding: 9px 32px;
    text-align: center;
    color: #fff;
    font-family: 'Inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
    border-radius: 34px;
    background: #890b0b;
  }
}
</style>
