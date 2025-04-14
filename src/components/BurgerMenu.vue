<template>
    <div>
      <!-- Бургер-меню -->
      <div class="burger-menu">
        <div class="burger-icon" :class="{ open: isOpen }" @click="toggleMenu">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
  
      <!-- Полноэкранное меню -->
      <div class="fullscreen-menu" :class="{ open: isOpen }">
        <ul>
          <li><a href="#h" @click="toggleMenu">Home</a></li>
          <li><a href="#a" @click="toggleMenu">About Us</a></li>
          <li><a href="#s" @click="toggleMenu">Services</a></li>
          <li><a href="#o" @click="toggleMenu">Our Work & Case Studies</a></li>
          <li><a href="#h" @click="toggleMenu">How We Work</a></li>
          <li><a href="#t" @click="toggleMenu">Technology & Expertise</a></li>
          <li><a href="#g" @click="toggleMenu">Get in Touch</a></li>
        </ul>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BurgerMenu',
    data() {
      return {
        isOpen: false, // Состояние меню (открыто/закрыто)
      };
    },
    methods: {
      toggleMenu() {
        this.isOpen = !this.isOpen; // Переключаем состояние
      },
    },
  };
  </script>
  
  <style scoped>
  /* Сбрасываем базовые стили */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Стили для бургер-меню */
  .burger-menu {
    position: relative;
    z-index: 1000;
    overflow: hidden;
  }
  
  .burger-icon {
    width: 50px;
    height: 50px;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  
  .burger-icon:hover {
    background: rgba(255, 255, 255, 0.4);
  }
  
  .burger-icon span {
    width: 24px;
    height: 3px;
    background: white;
    margin: 3px 0;
    transition: all 0.3s ease;
  }
  
  /* Стили для состояния "открыто" (крестик) */
  .burger-icon.open span:nth-child(1) {
    transform: rotate(45deg) translate(5px, 5px);
  }
  
  .burger-icon.open span:nth-child(2) {
    opacity: 0;
  }
  
  .burger-icon.open span:nth-child(3) {
    transform: rotate(-45deg) translate(5px, -5px);
  }
  
  /* Полноэкранное меню */
  .fullscreen-menu {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.1); /* Немного белый фон */
    backdrop-filter: blur(10px); /* Размытие фона */
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    visibility: hidden;
    transition: all 0.3s ease;
    z-index: 999;
  }
  
  .fullscreen-menu.open {
    opacity: 1;
    visibility: visible;
  }
  
  .fullscreen-menu ul {
    list-style: none;
    text-align: center;
  }
  
  .fullscreen-menu ul li {
    margin: 20px 0;
  }
  
  .fullscreen-menu ul li a {
    color: white;
    font-size: 24px;
    text-decoration: none;
    font-family: Arial, sans-serif;
    transition: color 0.3s ease;
  }
  
  .fullscreen-menu ul li a:hover {
    color: #fcd116; /* Цвет акцента */
  }
  </style>