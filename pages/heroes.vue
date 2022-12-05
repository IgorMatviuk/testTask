<template>
  <div class="container-large">
    <Breadcrumbs />
    <div class="heroes">
      <div class="heroes__title-block">
        <div class="heroes__title-block__left">
          <h1>Наши Герои</h1>
          <div class="heroes__title-block__left__btn">
            <button>Как попасть в базу?</button>
            <div class="heroes__title-block__left__btn-mob">
              <button>Фильтр</button>
            </div>
          </div>
        </div>
        <div class="heroes__title-block__left__select">
          <select name="" id="">
            <option value="">Сфера деятельности</option>
          </select>
          <select name="" id="">
            <option value="">Города</option>
          </select>
        </div>
      </div>
      <div class="heroes__cards">
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__card">
          <div class="heroes__cards__card__image">
            <img src="../assets/img/photo/base/1.png" alt="" />
            <div class="heroes__cards__card__image__overlay">
              <div class="heroes__cards__card__image__overlay__block">
                Общепит
              </div>
            </div>
          </div>
          <h1>Cofix</h1>
          <p>Международная сеть кофеен</p>
          <h2>Красноярск</h2>
          <div class="eroes__cards__card__line"></div>
        </div>
        <div class="heroes__cards__rek">
          <img src="../assets/img/photo/ads.png" alt="" />
        </div>
      </div>
      <div class="heroes__load-block">
        <div></div>
        <div class="heroes__load-block__button">
          <button>Загрузить ещё</button>
        </div>
        <div class="heroes__load-block__up">
          <img src="../assets/img/hero/btnUp.svg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Breadcrumbs from "../components/Breadcrumbs.vue";
export default {
  components: {
    Breadcrumbs,
  },
};
</script>

<style>
</style>