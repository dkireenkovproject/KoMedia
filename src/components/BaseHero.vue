<template>
  <section class="hero">
    <div class="container">
      <div class="hero__wrapper">
        <ul class="list-reset hero__items">
          <li class="hero__item"><img class="hero__img" src="/img/IMG_2494.png" alt="hero1" /></li>
          <li class="hero__item hero__dop">
            <img class="hero__img" src="/img/IMG_2495.png" alt="hero1" />
          </li>
          <li class="hero__item"><img class="hero__img" src="/img/IMG_2497.png" alt="hero1" /></li>
          <img class="hero__imgVector" src="/img/vector321.svg" alt="vector" />
        </ul>
      </div>
    </div>
    <img class="hero__imgVector2" src="/img/hero9301.jpg" alt="vector" />
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.hero {
  padding: 130px 0 0 0;
  margin-bottom: 50px;
  background-image: url(/img/Layer.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  background-position: top;
  min-height: 560px;
  z-index: 1;
  @media (max-width: 930px) {
    margin-bottom: 350px;
    min-height: 590px;
    background-size: 100% 90%;
  }

  @media (max-width: 716px) {
    padding: 120px 0 0 0;
    margin-bottom: 320px;
    background-size: 100% 80%;
  }
  @media (max-width: 492px) {
    padding: 60px 0 0 0;
    background-size: 100% 50%;
    margin-bottom: 150px;
  }
  @media (max-width: 400px) {
    padding: 50px 0 0 0;
    background-size: 100% 40%;
    margin-bottom: 15px;
  }
  @media (max-width: 372px) {
    padding: 60px 0 0 0;
    background-size: 100% 40%;
    margin-bottom: 0;
    min-height: 538px;
  }
  &__items {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 85px;
    width: 100%;
  }

  &__dop {
    @media (max-width: 930px) {
      display: none;
    }
  }
  &__imgVector {
    display: none;
    @media (max-width: 930px) {
      display: block;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: 999;
      min-width: 250px;
      min-height: 70px;
    }
    @media (max-width: 798px) {
      height: 310px;
    }
    @media (max-width: 726px) {
      height: 300px;
    }
    @media (max-width: 668px) {
      height: 250px;
    }
    @media (max-width: 562px) {
      height: 190px;
    }
    @media (max-width: 486px) {
      min-width: 200px;
      height: 160px;
    }
    @media (max-width: 400px) {
      min-width: 150px;
      height: 130px;
    }
  }
  &__imgVector2 {
    display: none;
    @media (max-width: 930px) {
      display: block;
      position: absolute;
      bottom: -82%;
      left: 0;
      width: 100%;
      height: 500px;
      z-index: -1;
      background-repeat: no-repeat;
    }
    @media (max-width: 716px) {
      bottom: -75%;
    }
    @media (max-width: 492px) {
      bottom: -50%;
    }
    @media (max-width: 466px) {
      bottom: -40%;
    }
    @media (max-width: 400px) {
      bottom: -20%;
      height: 400px;
    }
    @media (max-width: 372px) {
      bottom: -10%;
      height: 350px;
    }
  }
  //   &__img {
  //     width: 350px;
  //     height: 278px;
  //   }
}
</style>
