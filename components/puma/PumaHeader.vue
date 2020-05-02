<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <PumaTitle></PumaTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import PumaTitle from '~/components/puma/PumaTitle.vue'

export default {
  components: {
    ProjectNav,
    PumaTitle
  }
}
</script>

<style scoped>

section {
    width: 100%;
    height: 80vh;
    background-image: url(../../assets/images/bg.jpg);
    background-position: center;
    background-size: cover;
    display: flex;
    justify-content: center;
    flex-direction: column;

}

</style>