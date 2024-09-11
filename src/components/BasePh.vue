<template>
  <section class="ph">
    <div class="container">
      <div class="ph__wrapperList">
        <ul class="list-reset ph__list">
          <li class="ph__item">
            <span class="ph__text"
              >Множество удобных предложения под ключ по выгодной цене без потери качества</span
            >
            <div class="ph__arrowWrap">
              <picture alt="arrow3">
                <source
                  class="ph__arrow12"
                  srcset="/img/112233445.png"
                  media="(max-width: 438px)"
                />
                <source
                  class="ph__arrow12"
                  srcset="/img/112233441.png"
                  media="(max-width: 586px)"
                />
                <source class="ph__arrow12" srcset="/img/11223344.png" media="(max-width: 712px)" />
                <img class="ph__arrow1" src="/img/112233.png" alt="arrow4" />
              </picture>
            </div>
          </li>
          <li class="ph__item">
            <span class="ph__text"
              >Медиа на мероприятия, конференции, свадьбы, корпоративы и всю event-сферу</span
            >
            <div class="ph__arrowWrap2">
              <picture alt="arrow3">
                <source
                  class="ph__arrow12"
                  srcset="/img/112233446.png"
                  media="(max-width: 438px)"
                />
                <source
                  class="ph__arrow12"
                  srcset="/img/112233442.png"
                  media="(max-width: 586px)"
                />
                <source
                  class="ph__arrow112"
                  srcset="/img/11223355.png"
                  media="(max-width: 712px)"
                />
                <img class="ph__arrow2" src="/img/11223334.png" alt="arrow5" />
              </picture>
            </div>
          </li>
        </ul>
      </div>
      <div class="ph__wrapper">
        <h2 class="ph__title">photo video reels live photo video reels live</h2>
        <img class="ph__img" src="/img/camera.png" alt="camera" />
      </div>
      <div class="ph__wrapperList2">
        <ul class="list-reset ph__list ph__list2">
          <li class="ph__item ph__itemDop">
            <div class="ph__arrowWrap">
              <picture alt="arrow3">
                <source class="ph__arrow12" srcset="/img/32.png" media="(max-width: 586px)" />
                <source class="ph__arrow12" srcset="/img/01.png" media="(max-width: 712px)" />
                <img class="ph__bottom" src="/img/11.png" alt="arrow4" />
              </picture>
            </div>
            <span class="ph__text2"
              >Постоянная связь с менеджером и его присутствие на вашей локации</span
            >
          </li>
          <li class="ph__item">
            <div class="ph__arrowWrap2">
              <picture alt="arrow3">
                <source class="ph__arrow12" srcset="/img/35.png" media="(max-width: 438px)" />
                <source class="ph__arrow12" srcset="/img/34.png" media="(max-width: 586px)" />
                <source class="ph__arrow12" srcset="/img/02.png" media="(max-width: 712px)" />
                <img class="ph__bottom" src="/img/12.png" alt="arrow5" />
              </picture>
            </div>
            <span class="ph__text2">Только лучшие специалисты и техника</span>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped lang="scss">
.ph {
  border-top: 1px solid #000;
  position: relative;
  padding: 450px 0 450px 0;
  @media (max-width: 930px) {
    padding: 450px 0 450px 0;
    border-top: none;
  }

  @media (max-width: 712px) {
    padding: 190px 0 190px 0;
  }
  &__wrapper {
    position: relative;
  }
  &__img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    @media (max-width: 930px) {
      width: 300px;
      height: 300px;
    }
    @media (max-width: 712px) {
      width: 180px;
      height: 180px;
      top: 60%;
      left: 50%;
      transform: translate(-50%, -40%);
    }
    @media (max-width: 511px) {
      width: 150px;
      height: 150px;
      top: 50%;
      left: 50%;
    }
    @media (max-width: 400px) {
      width: 110px;
      height: 110px;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
  }
  &__title {
    margin: 0;
    color: #d9d9d9;
    text-align: center;
    text-shadow: 36px 45px 26.6px rgba(0, 0, 0, 0.25);
    font-family: 'Antonio';
    font-size: 90px;
    font-style: normal;
    font-weight: 400;
    line-height: 90%; /* 115.2px */
    letter-spacing: -0.64px;
    text-transform: uppercase;
    @media (max-width: 1340px) {
      font-size: 60px;
    }
    @media (max-width: 930px) {
      font-size: 40px;
      letter-spacing: normal;
    }
    @media (max-width: 712px) {
      font-size: 30px;
    }
    @media (max-width: 566px) {
      font-size: 25px;
    }
    @media (max-width: 474px) {
      font-size: 16px;
    }
  }
  &__text {
    display: block;
    text-align: center;
    margin-bottom: 30px;
    color: rgba(255, 255, 255, 0.7);
    font-family: 'Inter';
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 21.6px */
    @media (max-width: 930px) {
      font-size: 12px;
      line-height: normal; /* 21.6px */
    }
    @media (max-width: 570px) {
      text-align: left;
    }
    @media (max-width: 438px) {
      font-size: 10px;
      margin-bottom: 20px;
    }
  }
  &__text2 {
    display: block;
    text-align: center;
    margin-bottom: 0;
    color: rgba(255, 255, 255, 0.7);
    font-family: 'Inter';
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 120%; /* 21.6px */
    @media (max-width: 930px) {
      font-size: 12px;
      line-height: normal; /* 21.6px */
    }
    @media (max-width: 570px) {
      text-align: left;
    }
    @media (max-width: 438px) {
      font-size: 10px;
    }
  }
  &__wrapperList {
    position: absolute;
    top: 25%;
    left: 20%;
    transform: translate(-10%, -50%);
    @media (max-width: 570px) {
      left: 10%;
      transform: translate(-5%, -50%);
    }
  }
  &__wrapperList2 {
    position: absolute;
    bottom: 21%;
    left: 20%;
    transform: translate(-10%, 50%);
    @media (max-width: 570px) {
      left: 10%;
      transform: translate(-5%, 50%);
    }
  }
  &__list {
    display: grid;
    gap: 20%;
    grid-template-columns: repeat(2, 1fr);
    @media (max-width: 826px) {
      gap: 10%;
    }
  }
  &__item {
    width: 100%;
  }
  &__arrowWrap {
    display: flex;
    justify-content: end;
    @media (max-width: 712px) {
      justify-content: center;
    }
  }
  &__arrowWrap2 {
    @media (max-width: 838px) {
      display: flex;
      justify-content: center;
    }
  }
  &__bottom {
    margin-bottom: 20px;
    @media (max-width: 712px) {
      margin-bottom: 0;
    }
  }
  &__itemDop {
    @media (max-width: 712px) {
      display: flex;
      flex-direction: column;
      justify-content: end;
    }
  }
}
</style>
