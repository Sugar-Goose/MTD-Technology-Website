<template>
    <a href="#" class="accent__button">Start a Project ></a>
</template>

<script>
export default {
    name: 'AccentButton',
}
</script>

<style scoped>
.accent_button {
    color: var(--main-color);
    leading-trim: both;
    text-edge: cap;
    font-family: "San Francisco";
    font-size: 18px;
    font-style: normal;
    font-weight: 500;
    line-height: 120%; /* 21.6px */
    text-transform: capitalize;
}
</style>