<template>
    <section id="header-section">
        <Navigation></Navigation>
        <Title></Title>
    </section>
</template>

<script>
import Navigation from '~/components/header/Navigation.vue'
import Title from '~/components/header/Title.vue'

export default {
  components: {
    Navigation,
    Title
  }
}
</script>

<style scoped>

section {
    width: 100%;
    height: 100vh;
    background-image: url(../../assets/images/bg.jpg);
    background-position: center;
    background-size: cover;
    display: flex;
    justify-content: center;
    flex-direction: column;

}

</style>