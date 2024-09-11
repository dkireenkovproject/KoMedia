<template>
  <section class="about">
    <span class="about__bg"></span>
    <div class="container">
      <div class="about__wrapper">
        <div class="about__content">
          <ul class="list-reset about__list">
            <h2 class="about__title">
              <img class="about__930" src="/img/arrow.svg" alt="1" />ЧТО МЫ ДЕЛАЕМ?
            </h2>
            <li class="about__item">
              <img class="about__930" src="/img/spisok.svg" alt="1" />ВИДЕОСЪЕМКА
            </li>
            <li class="about__item">
              <img class="about__930" src="/img/spisok.svg" alt="1" />МОНТАЖ
            </li>
            <li class="about__item">
              <img class="about__930" src="/img/spisok.svg" alt="1" />ФОТО
            </li>
            <li class="about__item">
              <img class="about__930" src="/img/spisok.svg" alt="1" />РИЛС
            </li>
            <li class="about__item">
              <img class="about__930" src="/img/spisok.svg" alt="1" />ТРАНСЛЯЦИЯ
            </li>
          </ul>
        </div>
        <div class="about__img">
          <img class="about__img1" src="/img/hero.png" alt="Image Description" />
          <img class="about__img2" src="/img/Vector1.png" alt="Image Description" />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.about {
  padding: 20px 0 150px 0;
  @media (max-width: 930px) {
    padding: 20px 0 30px 0;
  }
  &__wrapper {
    padding-top: 100px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 30px;
    height: 100%;
    width: 100%;
    z-index: 2;
    @media (max-width: 511px) {
      padding-top: 110px;
    }
    @media (max-width: 451px) {
      gap: 10px;
    }
    @media (max-width: 387px) {
      padding-top: 90px;
    }
  }
  &__bg {
    display: block;
    position: absolute;
    width: 100%;
    min-height: 189px;
    background-image: url(/img/Vector.png);
    background-repeat: no-repeat;
    background-size: 100% 100%; /* Полное растягивание по ширине и высоте */
    background-position: center;
    z-index: 999;
    @media (max-width: 930px) {
      min-height: 150px;
    }
    @media (max-width: 758px) {
      min-height: 150px;
      background-image: url(/img/Layer4.png);
    }
    @media (max-width: 587px) {
      min-height: 130px;
    }
    @media (max-width: 387px) {
      min-height: 110px;
    }
  }
  &__item {
    display: flex;
    align-items: center;
    gap: 10px;
    color: rgba(255, 255, 255, 0.8);
    font-family: 'Inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    text-transform: uppercase;
    @media (max-width: 930px) {
      font-size: 16px;
    }
    @media (max-width: 692px) {
      font-size: 14px;
    }
    @media (max-width: 511px) {
      font-size: 11px;
    }
    @media (max-width: 387px) {
      font-size: 10px;
    }
  }
  &__list {
    display: flex;
    flex-direction: column;
    gap: 26px;
    @media (max-width: 477px) {
      gap: 20px;
    }
    @media (max-width: 387px) {
      gap: 15px;
    }
  }
  &__content {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  &__title {
    margin: 0;
    display: flex;
    align-items: center;
    gap: 10px;
    color: rgba(255, 255, 255, 0.8);
    font-family: 'Inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 800;
    text-transform: uppercase;
    @media (max-width: 930px) {
      font-size: 18px;
    }
    @media (max-width: 692px) {
      font-size: 16px;
    }
    @media (max-width: 511px) {
      font-size: 12px;
    }
    @media (max-width: 387px) {
      font-size: 11px;
    }
  }
  &__img {
    position: relative;
  }
  &__img1 {
    z-index: 3;
  }
  &__img2 {
    position: absolute;
    bottom: -50px;
    left: 0;
    width: 100%;
    min-height: 250px;
    @media (max-width: 930px) {
      min-height: 170px;
    }
    @media (max-width: 758px) {
      min-height: 130px;
    }
    @media (max-width: 511px) {
      min-height: 100px;
    }
  }
  &__930 {
    @media (max-width: 930px) {
      display: none;
    }
  }
}
</style>
