<template>
    <section id="project-section">
        <AboutTitle></AboutTitle>
        <AboutContainer></AboutContainer>
    </section>
</template>

<script>
import AboutTitle from '~/components/about/AboutTitle.vue'
import AboutContainer from '~/components/about/AboutContainer.vue'

export default {
  components: {
      AboutTitle,
      AboutContainer
  }
}
</script>

<style scoped>

#project-section {
    width: 100%;
    height: 100vh;
    display: grid;
    grid-template-rows: 30% 70%;
    background-color: #fdfdfd;
    padding: 4rem 4rem;

}

</style>