<template>
  <footer class="footer">
    <div class="footer__container">
      <div class="footer__logo">
        <img src="../assets/img/footer/logo.svg" alt="" />
      </div>
      <div class="footer__menu">
        <ul>
          <li>О редакции</li>
          <li>Популярное</li>
          <li>База контактов</li>
          <li>Новости</li>
          <li>Пользовательское соглашение</li>
        </ul>
      </div>
      <div class="footer__copy">
        <p>
          © ООО «СИБИРЬ РАБОТАЕТ», 2022. Сообщения и материалы сетевого издания
          «СИБИРЬ РАБОТАЕТ» (зарегистрировано Федеральной службой по надзору в
          сфере связи, информационных технологий и массовых коммуникаций
          (Роскомнадзор) 03.12.2022 за номером ЭЛ №ФС77-82385) сопровождаются
          пометкой «СИБИРЬ РАБОТАЕТ». Отдельные публикации могут содержать
          информацию, не предназначенную для пользователей до 18 лет.
        </p>
      </div>
      <div class="footer__social">
        <div class="button-blue">
          <button><p>Написать нам</p></button>
        </div>
        <div class="footer__social__icons">
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                d="M16 18.8C14.5 18.8 13.2 17.6 13.2 16C13.2 14.5 14.4 13.2 16 13.2C17.5 13.2 18.8 14.4 18.8 16C18.8 17.5 17.5 18.8 16 18.8Z"
                fill="#EEF0F3"
              />
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M19.4 9.2H12.6C11.8 9.3 11.4 9.4 11.1 9.5C10.7 9.6 10.4 9.8 10.1 10.1C9.86261 10.3374 9.75045 10.5748 9.61489 10.8617C9.57916 10.9373 9.5417 11.0166 9.5 11.1C9.48453 11.1464 9.46667 11.1952 9.44752 11.2475C9.34291 11.5333 9.2 11.9238 9.2 12.6V19.4C9.3 20.2 9.4 20.6 9.5 20.9C9.6 21.3 9.8 21.6 10.1 21.9C10.3374 22.1374 10.5748 22.2495 10.8617 22.3851C10.9374 22.4209 11.0165 22.4583 11.1 22.5C11.1464 22.5155 11.1952 22.5333 11.2475 22.5525C11.5333 22.6571 11.9238 22.8 12.6 22.8H19.4C20.2 22.7 20.6 22.6 20.9 22.5C21.3 22.4 21.6 22.2 21.9 21.9C22.1374 21.6626 22.2495 21.4252 22.3851 21.1383C22.4209 21.0626 22.4583 20.9835 22.5 20.9C22.5155 20.8536 22.5333 20.8048 22.5525 20.7525C22.6571 20.4667 22.8 20.0762 22.8 19.4V12.6C22.7 11.8 22.6 11.4 22.5 11.1C22.4 10.7 22.2 10.4 21.9 10.1C21.6626 9.86261 21.4252 9.75045 21.1383 9.61488C21.0627 9.57918 20.9833 9.54167 20.9 9.5C20.8536 9.48453 20.8048 9.46666 20.7525 9.44752C20.4667 9.3429 20.0762 9.2 19.4 9.2ZM16 11.7C13.6 11.7 11.7 13.6 11.7 16C11.7 18.4 13.6 20.3 16 20.3C18.4 20.3 20.3 18.4 20.3 16C20.3 13.6 18.4 11.7 16 11.7ZM21.4 11.6C21.4 12.1523 20.9523 12.6 20.4 12.6C19.8477 12.6 19.4 12.1523 19.4 11.6C19.4 11.0477 19.8477 10.6 20.4 10.6C20.9523 10.6 21.4 11.0477 21.4 11.6Z"
                fill="#EEF0F3"
              />
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23858 2.23858 0 5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5ZM12.6 7.7H19.4C20.3 7.8 20.9 7.9 21.4 8.1C22 8.4 22.4 8.6 22.9 9.1C23.4 9.6 23.7 10.1 23.9 10.6C24.1 11.1 24.3 11.7 24.3 12.6V19.4C24.2 20.3 24.1 20.9 23.9 21.4C23.6 22 23.4 22.4 22.9 22.9C22.4 23.4 21.9 23.7 21.4 23.9C20.9 24.1 20.3 24.3 19.4 24.3H12.6C11.7 24.2 11.1 24.1 10.6 23.9C10 23.6 9.6 23.4 9.1 22.9C8.6 22.4 8.3 21.9 8.1 21.4C7.9 20.9 7.7 20.3 7.7 19.4V12.6C7.8 11.7 7.9 11.1 8.1 10.6C8.4 10 8.6 9.6 9.1 9.1C9.6 8.6 10.1 8.3 10.6 8.1C11.1 7.9 11.7 7.7 12.6 7.7Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                d="M16.0309 9.46832C17.1335 9.46832 18.0329 10.3677 18.0329 11.4703C18.0329 12.5728 17.1335 13.4721 16.0309 13.4721C14.9285 13.4721 14.0291 12.5728 14.0291 11.4703C14 10.3677 14.8995 9.46832 16.0309 9.46832Z"
                fill="#EEF0F3"
              />
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M5 0C2.23858 0 0 2.23858 0 5V27C0 29.7614 2.23858 32 5 32H27C29.7614 32 32 29.7614 32 27V5C32 2.23858 29.7614 0 27 0H5ZM16.0309 16.3155C18.7003 16.3155 20.8763 14.1395 20.8763 11.4703C20.8763 8.80101 18.7003 6.625 16.0309 6.625C13.3327 6.625 11.1567 8.80101 11.1567 11.4703C11.1567 14.1395 13.3327 16.3155 16.0309 16.3155ZM17.9749 20.2904C18.9613 20.0583 19.9188 19.6811 20.7892 19.1299C21.4565 18.7236 21.6596 17.8243 21.2244 17.1569C20.8183 16.4896 19.9188 16.2865 19.2515 16.7217C17.2785 17.9693 14.6964 17.9693 12.7235 16.7217C12.0562 16.3156 11.1858 16.4896 10.7506 17.1569C10.3734 17.8243 10.5765 18.6947 11.2438 19.1008C12.1142 19.6521 13.0716 20.0292 14.0581 20.2613L11.3599 22.9596C10.8086 23.5109 10.8086 24.4103 11.3599 24.9616C11.65 25.2517 11.9982 25.3677 12.3753 25.3677C12.7525 25.3677 13.1007 25.2227 13.3908 24.9616L16.06 22.2923L18.7293 24.9616C19.2805 25.5128 20.18 25.5128 20.7312 24.9616C21.2824 24.4103 21.2824 23.5109 20.7312 22.9596L17.9749 20.2904Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23858 2.23858 0 5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5ZM16 8C20.4 8 24 11.6 24 16C24 20 21.1 23.4 17.1 24V18.3H19L19.4 16H17.2V14.5C17.2 13.9 17.5 13.3 18.5 13.3H19.5V11.3C19.5 11.3 18.6 11.1 17.7 11.1C15.9 11.1 14.7 12.2 14.7 14.2V16H12.7V18.3H14.7V23.9C10.9 23.3 8 20 8 16C8 11.6 11.6 8 16 8Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23858 2.23858 0 5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5ZM22.1 11.5C22.8 11.4 23.4 11.3 24 11C23.6 11.7 23 12.3 22.3 12.7C22.5 17.4 19.1 22.5 13 22.5C11.2 22.5 9.5 21.9 8 21C9.7 21.2 11.5 20.7 12.7 19.8C11.2 19.8 10 18.8 9.6 17.5C10.1 17.6 10.6 17.5 11.1 17.4C9.6 17 8.5 15.6 8.5 14.1C9 14.3 9.5 14.5 10 14.5C8.6 13.5 8.1 11.6 9 10.1C10.7 12.1 13.1 13.4 15.8 13.5C15.3 11.5 16.9 9.5 19 9.5C19.9 9.5 20.8 9.9 21.4 10.5C22.2 10.3 22.9 10.1 23.5 9.7C23.3 10.5 22.8 11.1 22.1 11.5Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23858 2.23858 0 5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5ZM8 16C8 11.6 11.6 8 16 8C20.4 8 24 11.6 23.9 15.6C23.9 20 20.3 23.6 15.9 23.6C15.1 23.6 14.3 23.5 13.6 23.3C13.9 22.8 14.2 22.2 14.4 21.6C14.5 21.2 15 19.4 15 19.4C15.3 19.9 16.1 20.4 17 20.4C19.6 20.4 21.3 18 21.3 14.9C21.3 12.5 19.3 10.3 16.2 10.3C12.4 10.3 10.5 13 10.5 15.3C10.5 16.7 11 17.9 12.1 18.4C12.3 18.5 12.4 18.4 12.5 18.2C12.6 18.1 12.7 17.7 12.7 17.6C12.7707 17.4586 12.7414 17.4172 12.6828 17.3343C12.6586 17.3 12.6293 17.2586 12.6 17.2C12.3 16.8 12.1 16.3 12.1 15.6C12.1 13.6 13.6 11.8 16 11.8C18.1 11.8 19.3 13.1 19.3 14.9C19.3 17.3 18.3 19.2 16.8 19.2C15.9 19.2 15.3 18.5 15.5 17.7C15.5835 17.2826 15.7192 16.8477 15.8491 16.4318C16.0303 15.8514 16.2 15.3078 16.2 14.9C16.2 14.2 15.8 13.7 15.1 13.7C14.3 13.7 13.6 14.6 13.6 15.8C13.6 16.6 13.9 17.1 13.9 17.1C13.9 17.1 13.1 20.8 12.9 21.5C12.8 22.1 12.8 22.6999 12.8 23.2999C10 22.0999 8 19.3 8 16Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M5 0C2.23858 0 0 2.23858 0 5V27C0 29.7614 2.23858 32 5 32H27C29.7614 32 32 29.7614 32 27V5C32 2.23858 29.7614 0 27 0H5ZM6.03027 16.0022C6.03027 10.4964 10.4938 6.03296 15.9997 6.03296L15.9996 6.03344C21.5061 6.03344 25.9692 10.4968 25.9692 16.0022C25.9692 21.5083 21.5061 25.9714 15.9997 25.9714C10.4938 25.9714 6.03027 21.5083 6.03027 16.0022ZM19.7168 20.6175C20.0097 20.7972 20.393 20.7044 20.5716 20.4115C20.7513 20.1187 20.6585 19.7365 20.3656 19.5568C17.7378 17.9508 14.4803 17.5769 10.6827 18.4449C10.3474 18.5211 10.1387 18.8544 10.2153 19.1889C10.2915 19.5234 10.6248 19.733 10.9592 19.6568C14.4294 18.8639 17.3761 19.1877 19.7168 20.6175ZM20.7228 17.9532C21.0882 18.1782 21.5668 18.0627 21.7918 17.6966V17.6968C22.0168 17.3318 21.9013 16.8532 21.5359 16.6282C18.4585 14.7371 13.9574 14.205 10.3368 15.3036C9.92646 15.4286 9.69468 15.8619 9.81849 16.273C9.94325 16.6833 10.3774 16.915 10.7885 16.7908C13.9581 15.8287 18.043 16.3057 20.7228 17.9532ZM10.3146 13.7171C13.3823 12.7861 18.6835 12.9615 21.8966 14.87H21.8971C22.3387 15.1331 22.9125 14.987 23.1744 14.5439C23.4375 14.1014 23.2923 13.5292 22.8482 13.2662C19.149 11.0701 13.2948 10.8636 9.77325 11.9326C9.28027 12.0824 9.00242 12.603 9.1517 13.0958C9.30099 13.5884 9.82194 13.8665 10.3146 13.7171Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon footer__social_icon-fix"></div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                d="M12.3336 13H11.1667C10.8333 13 10.7666 13.1569 10.7666 13.3299C10.7666 13.639 11.1622 15.1716 12.6087 17.1986C13.573 18.5829 14.9316 19.3333 16.1679 19.3333C16.9096 19.3333 17.0014 19.1667 17.0014 18.8796V17.8333C17.0014 17.5 17.0717 17.4335 17.3065 17.4335C17.4796 17.4335 17.7763 17.52 18.4687 18.1874C18.7042 18.4229 18.8812 18.6197 19.0253 18.7801C19.3654 19.1583 19.5228 19.3333 19.8354 19.3333H21.0023C21.3357 19.3333 21.5024 19.1667 21.4063 18.8378C21.301 18.51 20.9233 18.0343 20.422 17.4706C20.2841 17.3076 20.1112 17.1383 19.9582 16.9885C19.8094 16.8428 19.6794 16.7154 19.6184 16.6301C19.4453 16.4076 19.4948 16.3087 19.6184 16.111C19.6184 16.111 21.0401 14.1086 21.1885 13.4289C21.2627 13.1816 21.1885 13 20.8356 13H19.6687C19.372 13 19.2352 13.1569 19.161 13.3299C19.161 13.3299 18.5676 14.7761 17.7269 15.7154C17.4549 15.9873 17.3313 16.0739 17.1829 16.0739C17.1087 16.0739 17.0014 15.9873 17.0014 15.7402V13.4289C17.0014 13.1322 16.9153 13 16.668 13H14.8342C14.6488 13 14.5373 13.1377 14.5373 13.2682C14.5373 13.3755 14.5985 13.4513 14.6767 13.5481C14.8033 13.7047 14.9741 13.9162 15.0009 14.4053V16.1233C15.0009 16.5 14.9329 16.5683 14.7845 16.5683C14.3889 16.5683 13.4266 15.1157 12.8559 13.4536C12.7441 13.1305 12.6319 13 12.3336 13Z"
                fill="#EEF0F3"
              />
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M5 0C2.23858 0 0 2.23858 0 5V27C0 29.7614 2.23858 32 5 32H27C29.7614 32 32 29.7614 32 27V5C32 2.23858 29.7614 0 27 0H5ZM8 15.6667C8 12.0526 8 10.2455 9.12276 9.12276C10.2455 8 12.0526 8 15.6667 8H16.3333C19.9474 8 21.7545 8 22.8772 9.12276C24 10.2455 24 12.0526 24 15.6667V16.3333C24 19.9474 24 21.7545 22.8772 22.8772C21.7545 24 19.9474 24 16.3333 24H15.6667C12.0526 24 10.2455 24 9.12276 22.8772C8 21.7545 8 19.9474 8 16.3333V15.6667Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5C0 2.23858 2.23858 0 5 0ZM16.6919 12.0074C15.2589 12.6034 12.3949 13.8371 8.09992 15.7083C7.40248 15.9856 7.03714 16.257 7.00388 16.5223C6.94767 16.9706 7.50915 17.1472 8.27374 17.3876C8.37774 17.4203 8.4855 17.4542 8.59598 17.4901C9.34822 17.7346 10.3601 18.0207 10.8862 18.0321C11.3633 18.0424 11.8959 17.8457 12.4839 17.4419C16.4968 14.7331 18.5683 13.3639 18.6983 13.3344C18.7901 13.3136 18.9172 13.2874 19.0034 13.3639C19.0895 13.4405 19.0811 13.5855 19.0719 13.6244C19.0163 13.8615 16.8123 15.9106 15.6717 16.971C15.3161 17.3015 15.0639 17.536 15.0124 17.5896C14.8969 17.7096 14.7791 17.823 14.666 17.9321C13.9672 18.6058 13.4431 19.111 14.695 19.936C15.2967 20.3325 15.7781 20.6603 16.2584 20.9874C16.7829 21.3446 17.306 21.7009 17.9829 22.1446C18.1554 22.2576 18.3201 22.375 18.4805 22.4894C19.0909 22.9246 19.6393 23.3155 20.3168 23.2532C20.7105 23.217 21.1172 22.8468 21.3237 21.7427C21.8118 19.1335 22.7712 13.4801 22.9929 11.1505C23.0123 10.9464 22.9879 10.6851 22.9683 10.5705C22.9486 10.4558 22.9076 10.2924 22.7586 10.1715C22.582 10.0283 22.3095 9.99805 22.1877 10.0001C21.6335 10.01 20.7834 10.3056 16.6919 12.0074Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                d="M18.6 16L14.4 13.6V18.4L18.6 16Z"
                fill="#EEF0F3"
              />
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23858 2.23858 0 5 0H27C29.7614 0 32 2.23858 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23858 32 0 29.7614 0 27V5ZM22.2 10.7C22.9 10.9 23.4 11.4 23.6 12.1C24 13.4 24 16 24 16C24 16 24 18.6 23.7 19.9C23.5 20.6 23 21.1 22.3 21.3C21 21.6 16 21.6 16 21.6C16 21.6 10.9 21.6 9.7 21.3C9 21.1 8.5 20.6 8.3 19.9C8 18.6 8 16 8 16C8 16 8 13.4 8.2 12.1C8.4 11.4 8.90001 10.9 9.60001 10.7C10.9 10.4 15.9 10.4 15.9 10.4C15.9 10.4 21 10.4 22.2 10.7Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M0 5C0 2.23859 2.23859 0 5 0H27C29.7614 0 32 2.23859 32 5V27C32 29.7614 29.7614 32 27 32H5C2.23859 32 0 29.7614 0 27V5ZM10.1192 8.04428C11.5906 6.95401 13.3296 6.29492 15.1421 6.13116V9.13037C13.9705 9.28226 12.8516 9.73083 11.8944 10.4401C10.696 11.3281 9.81464 12.5778 9.38043 14.0048C8.9462 15.4319 8.98212 16.9607 9.48282 18.3657C9.98355 19.7708 10.9225 20.9778 12.1614 21.8086C13.4002 22.6394 14.8733 23.05 16.3633 22.9801C17.8532 22.9101 19.2812 22.363 20.4367 21.4198C21.5921 20.4763 22.4138 19.1867 22.7806 17.7409C23.0365 16.7324 23.0615 15.6852 22.8611 14.6755L25.3796 12.6508L25.3779 12.6345C26.0578 14.5046 26.1617 16.5392 25.6709 18.4741C25.1469 20.5395 23.9731 22.3819 22.3224 23.7296C20.6718 25.0771 18.6317 25.8586 16.5032 25.9586C14.3747 26.0585 12.2703 25.4719 10.5005 24.285C8.7308 23.0982 7.38934 21.3739 6.67404 19.3667C5.95874 17.3594 5.90744 15.1754 6.52774 13.1368C7.14804 11.0982 8.4071 9.31293 10.1192 8.04428ZM23.4911 9.47055L23.4806 9.44412C22.0565 7.83578 20.1191 6.69235 17.9251 6.27036V13.2277C17.386 12.8637 16.7361 12.6512 16.0367 12.6512C14.1703 12.6512 12.6573 14.1642 12.6573 16.0305C12.6573 17.8969 14.1703 19.4099 16.0367 19.4099C17.903 19.4099 19.416 17.8969 19.416 16.0305V9.94736C20.3759 10.4817 21.196 11.2367 21.8081 12.1437L23.4911 9.47055Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
          <div class="footer__social__icons__icon">
            <svg
              width="32"
              height="32"
              viewBox="0 0 32 32"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                class="social-icon-fill"
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M5 0C2.23858 0 0 2.23858 0 5V27C0 29.7614 2.23858 32 5 32H27C29.7614 32 32 29.7614 32 27V5C32 2.23858 29.7614 0 27 0H5ZM24.378 10.2162C25.2738 10.2162 26 9.49624 26 8.60811C26 7.71997 25.2738 7 24.378 7C23.4823 7 22.7561 7.71997 22.7561 8.60811C22.7561 9.49624 23.4823 10.2162 24.378 10.2162ZM19.9756 9.75676H7V24H10.7073V18.9459H16.7317L20.439 24H24.1463L20.439 18.9459L20.4225 18.9195C22.2593 18.7007 23.6829 17.1503 23.6829 15.2703V13.4324C23.6829 11.4024 22.0231 9.75676 19.9756 9.75676ZM10.7073 12.5135H19.0488C19.5607 12.5135 19.9756 12.9249 19.9756 13.4324V15.2703C19.9756 15.7778 19.5607 16.1892 19.0488 16.1892H10.7073V12.5135Z"
                fill="#EEF0F3"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
    <div class="footer__bottom">
      <img src="../assets/img/footer/logoAlente.svg" alt="" />
    </div>
  </footer>
</template>