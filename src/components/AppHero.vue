<script>
import AppTitle from '../components/AppTitle.vue'

export default {
    name: "AppHero",
    components: {
        AppTitle
    }
}
</script>

<template>
    <div>
        <AppTitle />
    </div>
</template>

<style scoped>
div {
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url(../assets/img/v627-aew-41-technologybackground.webp);
    background-size: cover;
    background-position: center;
    height: 100vh;
    padding: 40px;
}
</style>