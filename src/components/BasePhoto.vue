<template>
  <section class="photo">
    <div class="container">
      <div class="photo__wrapper">
        <h2 class="photo__title">Photos</h2>
        <div class="photo__content">
          <div class="photo__img1">
            <img src="/img/img1.png" alt="photo" width="100%" height="100%" />
          </div>
          <div class="photo__img2">
            <img src="/img/img2.png" alt="photo" width="100%" height="100%" />
          </div>
        </div>
        <div class="photo__wrap930">
          <img src="/img/9301.jpg" alt="photo" width="100%" height="100%" />
          <img src="/img/9302.jpg" alt="photo" width="100%" height="100%" />
          <img src="/img/9303.jpg" alt="photo" width="100%" height="100%" />
          <img src="/img/9304.jpg" alt="photo" width="100%" height="100%" />
          <img src="/img/9305.jpg" alt="photo" width="100%" height="100%" />
        </div>
        <div class="photo__content930">
          <span class="photo__text">Больше наших работ</span>
          <span class="photo__text2">фото видео рилс трансляция</span>
          <a class="photo__link" href="#">Смотреть</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.photo {
  border-top: 1px solid #000;
  padding-bottom: 50px;
  @media (max-width: 930px) {
    border-top: none;
  }
  &__title {
    color: #d9d9d9;
    text-shadow: 36px 45px 26.6px rgba(0, 0, 0, 0.25);
    font-family: 'Antonio';
    font-size: 64px;
    font-style: normal;
    font-weight: 400;
    line-height: 90%; /* 57.6px */
    letter-spacing: -0.32px;
    text-transform: uppercase;
    @media (max-width: 930px) {
      text-align: center;
    }
    @media (max-width: 548px) {
      font-size: 50px;
    }
    @media (max-width: 450px) {
      font-size: 30px;
    }
  }
  &__content {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 60px;
    @media (max-width: 930px) {
      display: none;
    }
  }
  &__wrap930 {
    display: none;
    @media (max-width: 930px) {
      margin-bottom: 70px;
      display: grid;
      grid-template-columns: repeat(1, 1fr);
      justify-content: center;
      gap: 50px;
    }
  }
  &__content930 {
    display: none;
    @media (max-width: 930px) {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 10px;
    }
  }
  &__text {
    color: rgba(255, 255, 255, 0.8);
    font-family: 'Inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 10.402px */
    text-transform: uppercase;
  }
  &__text2 {
    color: rgba(151, 16, 16, 0.8);
    font-family: 'Inter';
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 10.402px */
  }
  &__link {
    padding: 10px 30px;
    color: #fff;
    font-family: 'Inter';
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
    border-radius: 34px;
    background: #890b0b;
  }
}
</style>
