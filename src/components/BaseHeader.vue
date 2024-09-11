<template>
  <section class="header">
    <div class="container">
      <div class="header__wrapper">
        <div class="header__logo">
          <img class="header__logoWh" src="/img/logo.png" alt="logo" />
          <div class="header__title-wrapper">
            <h1 class="header__title">
              Агентство, предоставляющее медиа услуги под ключ удобно, быстро, выгодно
            </h1>
            <div class="header__line">
              <h1 class="header__title2">Агентство, предоставляющее медиа услуги под ключ</h1>
              <span class="header__titleDesc">удобно, быстро, выгодно</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.header {
  padding: 20px 0;
  &__wrapper {
    padding: 50px 0 0 0;
  }
  &__logo {
    display: flex;
    gap: 5px;
  }
  &__title {
    color: rgba(255, 255, 255, 0.8);
    text-align: bottom;
    font-family: 'Inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 20.804px */
    text-transform: uppercase;
    @media (max-width: 930px) {
      display: none;
    }
  }
  &__logoWh {
    @media (max-width: 930px) {
      width: 176px;
      height: 175px;
    }
    @media (max-width: 466px) {
      width: 110px;
      height: 110px;
    }
  }
  &__title-wrapper {
    display: flex;
    align-items: flex-end;
    max-width: 520px;
  }
  &__line {
    display: none;
    @media (max-width: 930px) {
      display: block;
    }
  }
  &__title2 {
    color: rgba(255, 255, 255, 0.8);
    font-family: 'Inter';
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 7.801px */
    text-transform: uppercase;
    @media (max-width: 466px) {
      font-size: 10px;
    }
  }
  &__titleDesc {
    display: block;
    font-family: 'Inter';
    color: rgba(255, 255, 255, 0.8);
    font-size: 10px;
    font-style: normal;
    font-weight: 400;
    text-transform: uppercase;
    @media (max-width: 466px) {
      font-size: 8px;
    }
  }
}
</style>
