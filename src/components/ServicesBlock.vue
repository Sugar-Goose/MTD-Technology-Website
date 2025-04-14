<template>
    <div class="main__container">
        <div class="header">
            <div class="header__card__bg">
                <svg xmlns="http://www.w3.org/2000/svg" width="230" height="220" viewBox="0 0 230 220" fill="none">
                    <ellipse cx="95.5" cy="95" rx="95.5" ry="95" fill="url(#paint0_linear_19_30)"/>
                    <ellipse cx="95.5" cy="95" rx="95.5" ry="95" fill="url(#paint1_linear_19_30)" fill-opacity="0.25"/>
                    <circle cx="190.5" cy="95.5" r="39.5" fill="url(#paint2_linear_19_30)"/>
                    <circle cx="190.5" cy="95.5" r="39.5" fill="url(#paint3_linear_19_30)" fill-opacity="0.25"/>
                    <circle cx="157.5" cy="157.5" r="62.5" fill="url(#paint4_linear_19_30)"/>
                    <circle cx="157.5" cy="157.5" r="62.5" fill="url(#paint5_linear_19_30)" fill-opacity="0.25"/>
                    <defs>
                        <linearGradient id="paint0_linear_19_30" x1="142.152" y1="190" x2="38.6956" y2="7.17686" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#D94C00"/>
                        <stop offset="1" stop-color="#FCD116"/>
                        </linearGradient>
                        <linearGradient id="paint1_linear_19_30" x1="142.152" y1="190" x2="38.6956" y2="7.17686" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#535353"/>
                        <stop offset="1" stop-color="white"/>
                        </linearGradient>
                        <linearGradient id="paint2_linear_19_30" x1="209.796" y1="135" x2="166.664" y2="59.1782" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#D94C00"/>
                        <stop offset="1" stop-color="#FCD116"/>
                        </linearGradient>
                        <linearGradient id="paint3_linear_19_30" x1="209.796" y1="135" x2="166.664" y2="59.1782" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#535353"/>
                        <stop offset="1" stop-color="white"/>
                        </linearGradient>
                        <linearGradient id="paint4_linear_19_30" x1="188.032" y1="220" x2="119.784" y2="100.029" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#D94C00"/>
                        <stop offset="1" stop-color="#FCD116"/>
                        </linearGradient>
                        <linearGradient id="paint5_linear_19_30" x1="188.032" y1="220" x2="119.784" y2="100.029" gradientUnits="userSpaceOnUse">
                        <stop stop-color="#535353"/>
                        <stop offset="1" stop-color="white"/>
                        </linearGradient>
                    </defs>
                </svg>
            </div>
            <div class="header__card__container">
                <div class="header__card">
                    <h3>Our Services</h3>
                </div>
            </div>
            <div class="header__text">
                <h6>We thrive on your product,<br>bringing dynamic, <span class="gradient__text gradient__text_1">modern</span><br><span class="gradient__text gradient__text_2">experience</span> and <span class="gradient__text gradient__text_3">perspective</span> to<br>everything we create</h6>
            </div>
        </div>
        <div class="content">
            <div class="content__text">
                <h4>OUR EXPERTISE</h4>
                <h5>We are a specialized digital<br>marketing agency on a mission to<br>elevate your business and help you<br>take the next big step toward<br>success.</h5>
                <a class="accent__button" href="#">Start a Project ></a>
            </div>
            <div class="content__block">
                <div class="skill__grid__left skills__grid">
                    <div class="skill">
                        <p>Visual Identity <span class="gradient__text gradient__text_2">&</span> Branding</p>
                    </div>
                    <div class="skill">
                        <p>Mobile Solutions <span class="gradient__text gradient__text_2">&</span> Apps</p>
                    </div>
                    <div class="skill">
                        <p>Growth <span class="gradient__text gradient__text_2">&</span> Digital Strategy</p>
                    </div>
                </div>
                <div class="skills__grid__right skills__grid">
                    <div class="skill">
                        <p>Business <span class="gradient__text gradient__text_2">&</span> Project</p>
                    </div>
                    <div class="skill">
                        <p>Web Design <span class="gradient__text gradient__text_2">&</span> Development</p>
                    </div>
                    <div class="skill">
                        <p>Coordination</p>
                    </div>
                </div>
            </div>
        </div>
        <RunningLine/>
    </div>
</template>

<script>
import RunningLine from './RunningLine.vue'
export default {
    name: 'ServicesBlock',
    components: {
        RunningLine
    }
}
</script>

<style scoped>
@import url('../global_stylesheet.css');

.content {
    display: flex;
    padding: 30px 0px;
    justify-content: space-around;
    align-items: center;
    gap: 10px;
    align-self: stretch;
}

.content__block {
    display: flex;
    align-items: center;
    gap: 10px;
    background: url('../assets/Logo_colorful.png');
    background-size: contain;
    background-repeat: no-repeat;
    background-position: 50% 50%;
    padding: 3rem;
}

.skills__grid {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.skill {
    display: flex;
    padding: 26px 15px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    border-radius: 24px;
    background: linear-gradient(100deg, rgba(255, 255, 255, 0.00) 0%, rgba(0, 0, 0, 0.50) 100.33%);
    backdrop-filter: blur(25px);
}

.header {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    height: fit-content;
    gap: 50px;
}

.header__card__container {
    padding: 0px 0px 0px 53px;
}

.content__text {
    display: flex;
    flex-direction: column;
    gap: 30px;
    color: #FFF;
}

.header__card {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 30px;
    align-items: center;
    gap: 10px;
    border-radius: 28px;
    background: linear-gradient(100deg, rgba(255, 255, 255, 0.00) 0%, rgba(255, 255, 255, 0.20) 100.33%);
    backdrop-filter: blur(25px);
    height: fit-content;
}

.accent__button {
    background: linear-gradient(100deg, rgba(252, 209, 22, 0.50) 17.54%, rgba(252, 209, 22, 0.10) 95.83%);
}

.header__card__bg {
    position: absolute;
}

.main__container {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    align-content: space-around;
    gap: 110px;
    padding: 3.125rem;
    width: 100vw;
    background-color: var(--background);
}

.gradient__text_1 {
    background: linear-gradient(90deg, #F09C1B 0%, #F7BB18 100%);
    
}

.gradient__text_2 {
    background: linear-gradient(90deg, #D53123 0%, #E2671E 100%);
}

.gradient__text_3 {
    background: linear-gradient(90deg, #EB891C 0%, #FCD116 100%);
}

.gradient__text {
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    leading-trim: both;
    text-edge: cap;
}

@media screen and (max-width: 1626px) {
    p {
        font-size: 1.2rem;
    }

    h4 {
        font-size: 2rem;
    }

    h5 {
        font-size: 1.75rem;
    }
}

@media screen and (max-width: 1392px) {
    p {
        font-size: 1rem;
    }

    h4 {
        font-size: 1.75rem;
    }

    h5 {
        font-size: 1.5rem;
    }
}

@media screen and (max-width: 1279px) {
    .header {
        display: flex;
        flex-direction: column;
    }

    .header__card__container {
        padding: 0;
    }

    .header__text, h4, h5 {
        text-align: center;
    }

    .accent__button {
        width: 100%;
        justify-content: center;
    }
    
    .content__text {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
    }

    .header__card__bg {
        display: none;
    }
    .content {
        display: flex;
        flex-wrap: wrap;
    }
}

@media screen and (max-width: 892px) {
    .header__card h3 {
        font-size: 2.25rem;
    }

    .header__text h6 {
        font-size: 1.75rem;
    }

    .content__text h4 {
        font-size: 2rem;
    }

    .content__text h5 {
        font-size: 1.5rem;
    }

    .skill p {
        font-size: 1rem;
    }

    .skill {
        padding: 16px 10px;
    }

    .main__container {
        gap: 20px;
        padding: 0px;
    }
}


@media screen and (max-width: 592px) {
    .header__card h3 {
        font-size: 1.35rem;
    }

    .header__text h6 {
        font-size: 1.25rem;
    }

    .content__text h4 {
        font-size: 1.5rem;
    }

    .content__text h5 {
        font-size: 1rem;
    }

    .skill p {
        font-size: 0.5rem;
    }

    .skill {
        padding: 10px 7px;
    }

    .main__container {
        height: fit-content;
        gap: 20px;
        padding: 0px;
    }
}
</style>