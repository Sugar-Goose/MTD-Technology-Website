<template>
    <div class="main__container">
        <div class="accent__info">
            <div class="logo">
                <svg width="300" height="103" viewBox="0 0 300 103" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M16.7137 0H50.7309L64.6917 58.3399H65.8715L98.7089 0H132.726L116.012 103H89.2706L98.9055 43.4531H98.119L66.2648 102.195H50.141L37.36 43.0508H36.5734L26.7419 103H0L16.7137 0Z" fill="white"/>
                    <path d="M128.116 22.5313L131.852 0H219.353L215.617 22.5313H185.336L172.358 103H145.42L158.397 22.5313H128.116Z" fill="white"/>
                    <path d="M241.178 103H201.851L218.565 0H256.318C266.674 0 275.326 2.12907 282.274 6.38721C289.221 10.6453 294.153 16.7308 297.07 24.6436C299.987 32.5563 300.56 41.9779 298.791 52.9082C297.087 63.4362 293.629 72.4386 288.418 79.9155C283.24 87.3924 276.62 93.1091 268.559 97.0654C260.529 101.022 251.402 103 241.178 103ZM233.017 79.2617H242.947C247.929 79.2617 252.369 78.3732 256.269 76.5962C260.202 74.7857 263.479 71.7681 266.101 67.5435C268.755 63.2853 270.672 57.4681 271.852 50.0918C272.966 43.1178 272.934 37.7365 271.754 33.9478C270.574 30.1255 268.329 27.4767 265.019 26.0015C261.709 24.4927 257.433 23.7383 252.189 23.7383H242.062L233.017 79.2617Z" fill="white"/>
                </svg>
            </div>
            <div class="accent__text">
                <h5>Ești pregătit pentru viitor. Noi îl construim.</h5>
            </div>
            <AccentButton/>
        </div>
        <div class="column">
            <div class="title">
                <h5>Explore</h5>
            </div>
            <div class="pills__container">
                <div class="pill">
                    <a href="#" class="pill__text">Home</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">About Us</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">Services</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">Our Work & Case Studies</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">How We Work</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">Technology & Expertise</a>
                </div>
                <div class="pill">
                    <a href="#" class="pill__text">Get in Touch</a>
                </div>
            </div>
        </div>

        <div class="column">
            <div class="title">
                <h5>Get in touch</h5>
            </div>
            <div class="pills__container">
                <div class="pill">
                    <p class="pill__text">+40 754 783 362</p>
                </div>
                <div class="pill">
                    <p class="pill__text">daniel@mtd.dev</p>
                </div>
                <div class="pill">
                    <p class="pill__text">Bulevardul Primăverii 50, București 011975, România</p>
                </div>
            </div>
        </div>

        <div class="light__bulb">
            <svg viewBox="0 0 457 320" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g filter="url(#filter0_f_21_951)">
                <circle cx="15" cy="442" r="192" fill="url(#paint0_linear_21_951)"/>
                </g>
                <defs>
                <filter id="filter0_f_21_951" x="-426.4" y="0.600006" width="882.8" height="882.8" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"/>
                <feGaussianBlur stdDeviation="124.7" result="effect1_foregroundBlur_21_951"/>
                </filter>
                <linearGradient id="paint0_linear_21_951" x1="15" y1="250" x2="119.5" y2="483.5" gradientUnits="userSpaceOnUse">
                <stop stop-color="#FFE100"/>
                <stop offset="1" stop-color="#CE1126"/>
                </linearGradient>
                </defs>
            </svg>
        </div>

        <div class="light__bulb__2">
            <svg viewBox="0 0 456 433" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g filter="url(#filter0_f_21_952)">
                <circle cx="406" cy="406" r="156" fill="url(#paint0_linear_21_952)"/>
                </g>
                <defs>
                <filter id="filter0_f_21_952" x="0.600006" y="0.600006" width="810.8" height="810.8" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
                <feFlood flood-opacity="0" result="BackgroundImageFix"/>
                <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"/>
                <feGaussianBlur stdDeviation="124.7" result="effect1_foregroundBlur_21_952"/>
                </filter>
                <linearGradient id="paint0_linear_21_952" x1="406" y1="250" x2="406" y2="562" gradientUnits="userSpaceOnUse">
                <stop stop-color="#FFE100"/>
                <stop offset="1" stop-color="#CE1126"/>
                </linearGradient>
                </defs>
            </svg>
        </div>
    </div>
</template>

<script>
import AccentButton from '../Items/AccentButton.vue';
export default {
    name: 'FooterBlock',
    components: {
        AccentButton
    }
}
</script>

<style scoped>
@import url('../../global_stylesheet.css');

.light__bulb svg {
    width: 100%;
}

.light__bulb {
    width: 30%;
    position: absolute;
    bottom: 0;
    left: 0;
    z-index: 1;
}

.light__bulb__2 {
    width: 30%;
    position: absolute;
    bottom: 0;
    right: 0;
    z-index: 1;
}

.light__bulb__2 svg {
    width: 100%;
}

.main__container {
    position: relative;
    display: flex;
    justify-content: space-around;
    gap: 50px;
    padding: 3.125rem;
    width: 100vw;
    height: 50vh;
    background-color: var(--background);
    color: #FFF;
    box-sizing: border-box;
}

.title {
    margin-bottom: 20px;
}

.title h5 {
    color: var(--accent-color);
}

.accent__info {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    flex: 1;
    height: 100%;
    z-index: 2;
}

.column {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    flex: 1;
    height: 100%;
    z-index: 2;
}

.pills__container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    flex-grow: 1;
}

.accent__button {
    background: linear-gradient(274deg, rgba(255, 255, 255, 0.38) 6.08%, rgba(255, 255, 255, 0.00) 93.92%);
}

.pill__text {
    font-size: 1.5rem;
}

a.pill__text:hover {
    text-decoration: underline;
}

@media screen and (max-width: 1440px) {
    h5 {
        font-size: 1.5rem;
    }

    .pill__text {
        font-size: 1.2rem;
    }
}

@media screen and (max-width: 1100px) {
    .main__container {
        display: flex;
        flex-direction: column;
        height: fit-content;
    }

    .logo {
        width: 30%;
    }

    .logo svg {
        width: 100%;
    }

    .accent__info {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 30px;
    }

    .pills__container {
        gap: 10px;
    }

    .column {
        justify-content: center;
        align-items: center;
    }

    .pill {
        width: 100%;
        display: flex;
        justify-content: center;
    }

    .pill__text {
        text-align: center;
    }

    .accent__text {
        text-align: center;
    }
}
</style>