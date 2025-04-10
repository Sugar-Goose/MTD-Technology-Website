<template>
  <div class="main__container">
    <video id="background-video" autoplay muted loop>
        <source src="../assets/bg_video.mp4" type="video/mp4">
        Your browser is not supporting video
    </video>
    <div class="header">
      <div class="logo">
        <svg width="120" height="22" viewBox="0 0 120 22" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g id="Logo">
          <g id="Logo_2">
          <g id="Logo_3">
          <path d="M6.94522 2H12.9396L15.3997 12.0385H15.6076L21.3941 2H27.3885L24.4433 19.7231H19.7309L21.4288 9.47692H21.2902L15.6769 19.5846H12.8357L10.5834 9.40769H10.4448L8.71235 19.7231H4L6.94522 2Z" fill="url(#paint0_linear_10_12)"/>
          <path d="M26.5761 5.87692L27.2345 2H42.6536L41.9952 5.87692H36.6592L34.3723 19.7231H29.6253L31.9122 5.87692H26.5761Z" fill="url(#paint1_linear_10_12)"/>
          <path d="M46.4994 19.7231H39.5695L42.5147 2H49.1674C50.9923 2 52.5169 2.36635 53.7412 3.09904C54.9655 3.83173 55.8346 4.87885 56.3486 6.24038C56.8625 7.60192 56.9636 9.22308 56.6518 11.1038C56.3515 12.9154 55.7422 14.4644 54.824 15.751C53.9115 17.0375 52.745 18.0212 51.3244 18.7019C49.9095 19.3827 48.3012 19.7231 46.4994 19.7231ZM45.0615 15.6385H46.8113C47.689 15.6385 48.4715 15.4856 49.1588 15.1798C49.8518 14.8683 50.4293 14.349 50.8913 13.6221C51.359 12.8894 51.6969 11.8885 51.9048 10.6192C52.1011 9.41923 52.0953 8.49327 51.8874 7.84135C51.6795 7.18365 51.2839 6.72788 50.7007 6.47404C50.1174 6.21442 49.3638 6.08462 48.4398 6.08462H46.6553L45.0615 15.6385Z" fill="url(#paint2_linear_10_12)"/>
          </g>
          </g>
          </g>
          <defs>
          <linearGradient id="paint0_linear_10_12" x1="79" y1="11" x2="-3" y2="2" gradientUnits="userSpaceOnUse">
          <stop offset="1" stop-color="white"/>
          </linearGradient>
          <linearGradient id="paint1_linear_10_12" x1="79" y1="11" x2="-3" y2="2" gradientUnits="userSpaceOnUse">
          <stop offset="1" stop-color="white"/>
          </linearGradient>
          <linearGradient id="paint2_linear_10_12" x1="79" y1="11" x2="-3" y2="2" gradientUnits="userSpaceOnUse">
          <stop offset="1" stop-color="white"/>
          </linearGradient>
          </defs>
          </svg>
      </div>
      <div class="nav__buttons">
        <div class="nav__pill"><a href="#h">Home</a></div>
        <div class="nav__pill"><a href="#a">About Us</a></div>
        <div class="nav__pill"><a href="#s">Services</a></div>
        <div class="nav__pill"><a href="#o">Our Work & Case Studie</a></div>
        <div class="nav__pill"><a href="#h">How We Work</a></div>
        <div class="nav__pill"><a href="#t">Technology & Expertise</a></div>
        <div class="nav__pill"><a href="#g">Get in Touch</a></div>
      </div>
      <div class="buttons">
        <div class="pill">
          <a href="#">
            <div class="pill__container">
              <svg xmlns="http://www.w3.org/2000/svg" width="27" height="27" viewBox="0 0 27 27" fill="none">
                <path d="M9.29883 20.2598H8V6H9.29883V20.2598Z" fill="white"/>
                <path d="M20.8516 19.166H13.7559V17.9834H20.8516V19.166Z" fill="white"/>
                <path d="M9.29883 20.2598H8V6H9.29883V20.2598Z" stroke="white"/>
                <path d="M20.8516 19.166H13.7559V17.9834H20.8516V19.166Z" stroke="white"/>
              </svg>
            </div>
          </a>
        </div>
        <div class="pill">
          <a href="#">
            <div class="pill__container">
              <svg width="27" height="28" viewBox="0 0 27 28" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <circle id="Flag" cx="13.5" cy="14" r="13.5" fill="url(#pattern0_10_22)"/>
                <defs>
                <pattern id="pattern0_10_22" patternContentUnits="objectBoundingBox" width="1" height="1">
                <use xlink:href="#image0_10_22" transform="matrix(0.00244603 0 0 0.00314156 -0.105629 -0.0159462)"/>
                </pattern>
                <image id="image0_10_22" data-name="Flag_of_Romania.svg.png" width="500" height="334" preserveAspectRatio="none" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfQAAAFOBAMAAACCqfKqAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAIVBMVEUAKn5FVmCXjj+pZTWxVDMAK39UY1z80RbdUCDOESb///8a1sQzAAAABXRSTlNVaI6ntArr8tcAAAABYktHRApo0PRWAAAAB3RJTUUH6AYXEw8mP7gt0gAAAXNJREFUeNrtz1EBgCAUBLCXgQhQhQpmIIJWoS0lji+3Bqsnb71x384rdXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV1dXV19b/XL2g9bsy8A0ioQLpS/nXAAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDI0LTA2LTIzVDE5OjE1OjM3KzAwOjAwRgAcowAAACV0RVh0ZGF0ZTptb2RpZnkAMjAyNC0wNi0yM1QxOToxNTozNyswMDowMDddpB8AAAAASUVORK5CYII="/>
                </defs>
              </svg>
            </div>
          </a>
        </div>
        <div class="pill">
          <a class="button__container" href="#">Career</a>
        </div>
      </div>
    </div>

    <div class="content">
      <div class="header__text">
        <h3 class="gradient__text">Transforming Business Excellence. Empowering Your Digital Journey.</h3>
      </div>
      <div class="buttons__container">
        <a href="#" class="content__button">
          <h4>Get started now</h4>
        </a>
        <div class="credentials">
          <h4>MTD Dev.</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainComp',
}
</script>

<style scoped>
@import url('../global_stylesheet.css');

.main__container {
  padding-top: 20px;
  width: 100vw;
  height: 100vh;
}

.content {
  display: flex;
  flex-direction: column;
  gap: 20px;
  position: absolute;
  top:50%;
  left:50%;
  width: fit-content;
  transform: translate(-50%, -50%);
}

.header__text {
  border-radius: 28px;
  background: linear-gradient(100deg, rgba(255, 255, 255, 0.00) 0%, rgba(0, 0, 0, 0.50) 100.33%);
  backdrop-filter: blur(25px);
  padding: 20px 50px;
}

.gradient__text {
  background: linear-gradient(91deg, #FFF2B9 9.68%, #FCD116 97.59%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  display: inline-block;
  font-weight: bold;
}

.buttons__container {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  align-self: stretch;
}

.content__button {
  height: 74px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 10px;
  flex: 1 0 0;
  border-radius: 17px;
  background: linear-gradient(280deg, rgba(252, 209, 22, 0.50) 0%, rgba(252, 209, 22, 0.10) 100%);
  -webkit-backdrop-filter: blur(25px);
  backdrop-filter: blur(25px);
  position: relative;
  overflow: hidden;
  transition: color 0.25s;
}

.content__button::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(280deg, rgba(255, 255, 255, 0.50) 0%, rgba(252, 209, 22, 0.10) 100%);
  border-radius: 17px;
  opacity: 0;
  transition: opacity 0.25s;
  z-index: -1;
}

.content__button:hover::after {
  opacity: 1;
}


.credentials {
  height: 74px;
  cursor: default;
  display: flex;
  padding: 0px 20px;
  
  align-items: center;
  gap: 10px;
  border-radius: 17px;
  background: linear-gradient(100deg, rgba(255, 255, 255, 0.00) 0%, rgba(255, 255, 255, 0.20) 100.33%);
  backdrop-filter: blur(7.449999809265137px);
}

.credentials h4, .content__button h4 {
  color: #FFF;
}

.header {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  display: flex;
  width: fill-container;
  height: 64px;
  padding: 0px 15px;
  justify-content: center;
  align-items: center;
  gap: 37px;
  border-radius: 103px;
  max-width: 100%;
  background: linear-gradient(90deg, rgba(255, 255, 255, 0.50) 0%, rgba(255, 255, 255, 0.00) 100%);
  backdrop-filter: blur(25px);
}

#background-video {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100vw;
  height: 100vh;
  min-width: 100%;
  min-height: 100%;
  -webkit-transform: translate(-50%, -50%);
  -moz-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  object-fit: cover;
  z-index: -1;
}

.nav__buttons {
  display: flex;
  justify-content: center;
  gap:20px;
  width: fit-content;
  align-items: center;
}

.nav__pill a {
  white-space: nowrap;
}

.nav__pill a:hover {
  color: var(--accent-color);
}

.buttons {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 12px;
}

.pill {
  width: fit-content;
}

.button__container {
  cursor: pointer;
  background-color: rgba(245, 246, 247, 0.13);
  display: flex;
  padding:12px 16px;
  justify-content: center;
  align-items: center;
  border-radius: 100px;
  transition: all 0.5s;
}

.button__container:hover {
  background-color: rgba(245, 246, 247, 0.373);
  transition: all 0.5s;
}

.pill__container {
  cursor: pointer;
  width: 38px;
  height: 38px;
  background-color: rgba(245, 246, 247, 0.13);
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 100px;
  transition: all 0.5s;
}

.pill__container:hover {
  background-color: rgba(245, 246, 247, 0.373);
  transition: all 0.5s;
}


/* Планшеты (ширина до 1024px) */
@media (max-width: 1024px) {
  .header {
    height: 50px; /* Уменьшаем высоту хедера */
    padding: 0 10px; /* Уменьшаем внутренние отступы */
    gap: 20px; /* Уменьшаем расстояние между элементами */
  }

  .logo svg {
    width: 100px; /* Уменьшаем логотип */
    height: 18px;
  }

  .nav__pill a {
    font-size: 14px; /* Уменьшаем размер текста в навигации */
  }

  .pill__container {
    width: 32px; /* Уменьшаем размер кнопок */
    height: 32px;
  }

  .pill__container svg {
    width: 20px; /* Уменьшаем иконки */
    height: 20px;
  }

  .button__container {
    font-size: 14px; /* Уменьшаем текст кнопки */
    padding: 8px 12px; /* Уменьшаем внутренние отступы */
  }
}


/* Media requests */

@media (max-width: 1366px) and (min-width: 1100px) {
  .header {
    height: 56px;
    padding: 0 12px;
    gap: 30px;
  }

  .logo svg {
    width: 110px;
    height: 20px;
  }

  .nav__buttons {
    gap: 15px;
  }

  .nav__pill a {
    font-size: 15px;
  }

  .pill__container {
    width: 34px;
    height: 34px;
  }

  .pill__container svg {
    width: 22px;
    height: 22px;
  }

  .button__container {
    font-size: 15px;
    padding: 8px 14px; 
  }
}


@media (max-width: 768px) {
  .header {
    height: 40px; 
    padding: 0 8px;
    gap: 15px;
    flex-wrap: nowrap; 
    overflow-x: auto; 
  }

  .logo svg {
    width: 80px;
    height: 14px;
  }

  .nav__buttons {
    gap: 10px;
  }

  .nav__pill a {
    font-size: 12px;
  }

  .pill__container {
    width: 28px;
    height: 28px;
  }

  .pill__container svg {
    width: 18px;
    height: 18px;
  }

  .button__container {
    font-size: 12px;
    padding: 6px 10px;
  }
}


@media (max-width: 480px) {
  .header {
    height: 36px;
    padding: 0 5px;
    gap: 10px;
  }

  .logo svg {
    width: 60px; 
    height: 12px;
  }

  .nav__buttons {
    gap: 8px;
  }

  .nav__pill a {
    font-size: 10px; 
  }

  .pill__container {
    width: 24px;
    height: 24px;
  }

  .pill__container svg {
    width: 16px;
    height: 16px;
  }

  .button__container {
    font-size: 10px;
    padding: 4px 8px;
  }
}
</style>
