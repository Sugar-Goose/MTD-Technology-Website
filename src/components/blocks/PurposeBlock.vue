<template>
    <div class="main__container">
        <div class="black__block"></div>
        <CubesModel class="model__3D"/>
        <div class="content">
            <div class="header__container">
                <h2 class="gradient__text">Our Purpose</h2>
            </div>
            <div class="text__container">
                <p>We are committed to guide <span class="highlighted__text">digital transformation</span> for organizations, companies, and brands. Our teams develop platforms and experiences, create marketing and communication solutions and design new products, services and business models for the digital age.</p>
                <p>We combine strategy, technology and creativity at the <span class="highlighted__text">highest level.</span> Weather your goal is to develop a platform, create marketing and communication solutions, design a new product, service, or business model, we are eager to collaborate. From concept to final version, we are committed to combine strategy, technology, and creativity to create an intuitive, engaging, and integrated product.</p>
                <p>For our clients, we rethink business and take <span class="highlighted__text">transformation to the next level</span> – as a partner for digital reinvention.</p>
                <p>Integrating our 7 years of experience with constant innovation, paired with commitment to create <span class="highlighted__text">unique and relevant</span> customer experiences we help achieve successful digital transformation.</p>
            </div>
        </div>
    </div>
</template>

<script>
import CubesModel from '../3d_items/CubesModel.vue';
export default {
    name: 'PurposeBlock',
    components: {
        CubesModel
    }
}
</script>

<style scoped>
@import url('../../global_stylesheet.css');

.highlighted__text {
    color: var(--accent-color);
}

.header__container {
    display: flex;
    margin-bottom: 50px;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
    border-radius: 25px;
    width: fit-content;
}

.text__container {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    align-self: stretch;
    border-radius: 25px;
}

.text__container p {
    font-size: 0.85rem;
    font-family: "sf_monolight";
}

.content {
    pointer-events: none;
    z-index: 2;
}

.gradient__text {
    background-clip: text;
    background: linear-gradient(129deg, #FCD116 29.12%, #db753a 86.58%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    leading-trim: both;
    text-edge: cap;
}

.model__3D {
    width: 100vw;
    height: 100vh;
    position: absolute;
    top:0;
    left:0;
    z-index: 0;
}

.black__block {
    width: 30%;
    height: 100px;
    background-color: var(--background);
    position: absolute;
    bottom:10%;
    right:0;
    pointer-events: none;
    z-index: 1;
}

.main__container {
    position: relative;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-content: space-around;
    padding: 3.125rem;
    gap: 50px;
    width: 100vw;
    height: 100vh;
    background-color: var(--background);
    color: #FFF;
}

@media screen and (max-width: 1100px) {
    .black__block {
        display: none;
    }

    .model__3D {
        display: none;
    }

    .header__container {
        width: 100%;
    }

    .header__container h2 {
        width: 100%;
        text-align: center;
    }

    .text__container {
        width: 70%;
    }

    .text__container p {
        text-align: center;
    }

    .main__container {
        padding: 0px;
    }

    .content {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
}

@media screen and (max-width: 767px) {
    .header__container h2 {
        font-size: 3rem;
    }

    .main__container {
        height: fit-content;
    }
}
</style>