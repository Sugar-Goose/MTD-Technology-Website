<template>
  <div class="marquee__container">
    <div class="marquee__wrapper">
      <div class="marquee__content">
        <span>Coordination</span>
        <span class="dot">•</span>
        <span>Visual Identity & Branding</span>
        <span class="dot">•</span>
        <span>Mobile Solutions & Apps</span>
        <span class="dot">•</span>
        <span>Growth & Digital Strategy</span>
        <span class="dot">•</span>
        <span>Business & Project</span>
        <span class="dot">•</span>
        <span>Web Design & Development</span>
        <span class="dot">•</span>
      </div>
      
      <div class="marquee__content" aria-hidden="true">
        <span>Coordination</span>
        <span class="dot">•</span>
        <span>Visual Identity & Branding</span>
        <span class="dot">•</span>
        <span>Mobile Solutions & Apps</span>
        <span class="dot">•</span>
        <span>Growth & Digital Strategy</span>
        <span class="dot">•</span>
        <span>Business & Project</span>
        <span class="dot">•</span>
        <span>Web Design & Development</span>
        <span class="dot">•</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'RunningLine',
}
</script>

<style scoped>
@import url('../global_stylesheet.css');

.marquee__container {
  width: 100vw;
  position: absolute;
  left:0;
  bottom: 0;
  overflow: hidden;
  background-color: var(--background);
  white-space: nowrap;
  margin: 0;
  padding: 0;
}

.marquee__wrapper {
  display: inline-flex;
  animation: marquee 30s linear infinite;
}

.marquee__content {
  display: inline-flex;
  align-items: center;
  gap: clamp(1rem, 2vw, 1.5rem);
  padding: 1rem 0;
}

.marquee__content span {
  color: var(--main-color);
  font-family: 'sf_monoregular';
  font-size: clamp(1rem, 2.5vw, 1.2rem);
  font-weight: 500;
  text-transform: capitalize;
}

.marquee__content .dot {
  color: var(--accent-color);
  font-size: clamp(1.2rem, 3vw, 1.5rem);
  font-weight: 700;
}

/* Анимация бегущей строки */
@keyframes marquee {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-50%);
  }
}

/* Адаптивность */
@media (max-width: 768px) {
  .marquee__content {
    gap: clamp(0.5rem, 1.5vw, 1rem);
  }

  .marquee__content span {
    font-size: clamp(0.8rem, 2.2vw, 1rem);
  }

  .marquee__content .dot {
    font-size: clamp(1rem, 2.5vw, 1.2rem);
  }
}

@media (max-width: 480px) {
  .marquee__content {
    gap: 0.5rem;
  }

  .marquee__content span {
    font-size: clamp(0.7rem, 2vw, 0.9rem);
  }

  .marquee__content .dot {
    font-size: clamp(0.8rem, 2.2vw, 1rem);
  }
}
</style>