<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <PipTitle></PipTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import PipTitle from '~/components/pip/PipTitle.vue'

export default {
  components: {
    ProjectNav,
    PipTitle
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