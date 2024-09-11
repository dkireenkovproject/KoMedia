<template>
  <section class="price">
    <div class="container">
      <div class="price__wrapper">
        <div class="price__content">
          <h3 class="price__title">Price</h3>
          <div class="price__cont">
            <span class="price__sub"
              >Время на локации - 5 часов, дополнительный час +20% от общей суммы</span
            >
          </div>
        </div>
        <div class="price__table">
          <ul class="list-reset price__list">
            <li class="price__item">
              <span class="price__span">Лайт пакет</span>
              <div class="price__desc">
                <span class="price__desc-title"
                  ><span style="color: #fff">Видео</span> - длительность до 3-х минут Фото от 50 в
                  обработке за час</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Фото</span> от 50 в обработке за час</span
                >
              </div>
              <a class="price__link" href="/">35.000</a>
            </li>
            <li class="price__item">
              <span class="price__span">Лайт пакет</span>
              <div class="price__desc">
                <span class="price__desc-title"
                  ><span style="color: #fff">Видео</span> - длительность до 8 минут, либо два видео
                  по 4 минуты</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Фото</span> от 150 в обработке за час</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Рилс -</span> 8 видео (каждое продолжительностью до
                  минуты)</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Трансляция</span> на одну камеру</span
                >
              </div>
              <a class="price__link" href="/">70.000</a>
            </li>
            <li class="price__item">
              <span class="price__span">Лайт пакет</span>
              <div class="price__desc">
                <span class="price__desc-title"
                  ><span style="color: #fff">Видео</span> - длительность 5 минут, либо два видео по
                  2 минуты</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Фото</span> от 100 в обработке за час</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Рилс -</span> 5 видео (каждое продолжительностью до
                  минуты)</span
                >
              </div>
              <a class="price__link" href="/">50.000</a>
            </li>
            <li class="price__item">
              <span class="price__span">Лайт пакет</span>
              <div class="price__desc">
                <span class="price__desc-title"
                  ><span style="color: #fff">Видео</span> - суммарная длительность до 15 минут</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Фото</span> от 200 в обработке за час</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Рилс</span> 15 видео (каждое продолжительностью до
                  минуты)</span
                >
                <span class="price__desc-title"
                  ><span style="color: #fff">Трансляция</span> на две камеры</span
                >
              </div>
              <a class="price__link" href="/">90.000</a>
            </li>
          </ul>
        </div>
        <div class="price__text">
          <p class="price__desc-span">
            Дополнительные услуги по каждому пакету уточняются у менеджера
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.price {
  padding: 50px 0 100px 0;
  border-bottom: 1px solid #000;
  @media (max-width: 930px) {
    border-bottom: none;
    padding: 50px 0 50px 0;
  }
  @media (max-width: 450px) {
    border-bottom: none;
    padding: 20px 0 20px 0;
  }
  &__content {
    margin-bottom: 40px;
    display: flex;
    gap: 30px;
    @media (max-width: 930px) {
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
  }
  &__title {
    margin: 0;
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
  &__sub {
    color: #fff;
    font-family: 'Inter';
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 15.603px */
    text-transform: uppercase;
    @media (max-width: 930px) {
      text-align: center;
    }
  }
  &__cont {
    display: flex;
    align-items: flex-end;
    max-width: 370px;
  }
  &__list {
    margin-bottom: 90px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    column-gap: 30%;
    row-gap: 60px;
    @media (max-width: 930px) {
      grid-template-columns: repeat(1, 1fr);
    }
    @media (max-width: 450px) {
      row-gap: 30px;
      margin-bottom: 50px;
    }
  }
  &__span {
    margin-bottom: 15px;
    display: block;
    color: #890b0b;
    font-family: 'Inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 26.005px */
    text-transform: uppercase;
    @media (max-width: 450px) {
      font-size: 16px;
    }
  }
  &__desc {
    display: flex;
    flex-direction: column;
    gap: 5px;
    margin-bottom: 30px;
  }
  &__desc-title {
    color: rgba(255, 255, 255, 0.7);
    font-family: 'inter';
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%;
    @media (max-width: 450px) {
      font-size: 14px;
    }
  }
  &__link {
    padding: 9px 32px;
    color: #fff;
    font-family: 'inter';
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
    border-radius: 43px;
    border: 1px solid #890b0b;
    @media (max-width: 450px) {
      padding: 5px 25px;
      font-size: 13px;
    }
  }
  &__text {
    display: flex;
    justify-content: center;
    @media (max-width: 930px) {
      justify-content: left;
    }
  }
  &__desc-span {
    margin: 0;
    max-width: 520px;
    color: rgba(255, 255, 255, 0.9);
    text-align: center;
    font-family: 'inter';
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 130.023%; /* 26.005px */
    text-transform: uppercase;
    @media (max-width: 930px) {
      text-align: left;
    }
    @media (max-width: 450px) {
      font-size: 14px;
      max-width: 100%;
    }
  }
}
</style>
