<template>
  <header class="header">
    <div class="header__container">
      <div class="header__menu">
        <svg
          @click="openMenuBar"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            class="header-menu-active"
            d="M1 3H22.2C22.8 3 23.2 2.6 23.2 2C23.2 1.4 22.8 1 22.2 1H1C0.4 1 0 1.4 0 2C0 2.6 0.4 3 1 3Z"
            fill="black"
          />
          <path
            class="header-menu-active"
            d="M22.2 11H1C0.4 11 0 11.4 0 12C0 12.6 0.4 13 1 13H22.2C22.8 13 23.2 12.6 23.2 12C23.2 11.4 22.8 11 22.2 11Z"
            fill="black"
          />
          <path
            class="header-menu-active"
            d="M22.2 21H1C0.4 21 0 21.4 0 22C0 22.6 0.4 23 1 23H22.2C22.8 23 23.2 22.6 23.2 22C23.2 21.4 22.8 21 22.2 21Z"
            fill="black"
          />
        </svg>
      </div>
      <div class="header__logo">
        <img src="../assets/img/header/logo-m.svg" alt="" />
      </div>
      <div class="header__search">
        <img src="../assets/img/header/Search.svg" alt="" />
      </div>
    </div>
    <div class="header__line"></div>
    <div class="header-menu-bar" v-if="IsMenuBarShow" @click="closeMenuBar">
      <NuxtLink to="/">Главная</NuxtLink>
      <NuxtLink to="/news">Новости</NuxtLink>
      <NuxtLink to="/heroes">Герои</NuxtLink>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      IsMenuBarShow: false
    };
  },
  methods: {
    openMenuBar() {
        this.IsMenuBarShow = true;
      },
      closeMenuBar() {
        this.IsMenuBarShow = false;
      },
  }
};
</script>
