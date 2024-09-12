<template>
  <section class="contact">
    <div class="container">
      <div class="contact__wrapper">
        <h3 class="contact__title">Contacts</h3>
        <span class="contact__text">Оформить заказ или задать вопрос </span>
        <a class="contact__link" href="/">написать</a>
        <a class="contact__tel" href="tel:+79266719933">8(926)-671-99-33</a>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.contact {
  padding: 190px 0 20px 0;
  @media (max-width: 930px) {
    padding: 100px 0 20px 0;
  }
  @media (max-width: 450px) {
    padding: 50px 0 0px 0;
  }
  &__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  &__title {
    margin: 0;
    margin-bottom: 30px;
    color: #d9d9d9;
    text-shadow: 36px 45px 26.6px rgba(0, 0, 0, 0.25);
    font-family: 'Antonio';
    font-size: 64px;
    font-style: normal;
    font-weight: 400;
    line-height: 90%; /* 57.6px */
    letter-spacing: -0.32px;
    text-transform: uppercase;
    @media (max-width: 548px) {
      font-size: 50px;
    }
    @media (max-width: 450px) {
      font-size: 30px;
    }
  }
  &__text {
    display: block;
    margin-bottom: 42px;
    color: rgba(255, 255, 255, 0.9);
    font-family: 'Inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 26.005px */
    text-transform: uppercase;
    @media (max-width: 450px) {
      margin-bottom: 30px;
      font-size: 14px;
    }
  }
  &__link {
    padding: 9px 32px;
    margin-bottom: 42px;
    border-radius: 34px;
    background: #890b0b;
    color: #fff;
    font-family: 'Inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
    @media (max-width: 450px) {
      margin-bottom: 30px;

      padding: 10px 30px;
      font-size: 14px;
    }
  }
  &__tel {
    color: rgba(255, 255, 255, 0.9);
    font-family: 'Inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 26.005px */
    text-transform: uppercase;
  }
}
</style>
