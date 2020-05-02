<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <StubuTitle></StubuTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import StubuTitle from '~/components/stubu/StubuTitle.vue'

export default {
  components: {
    ProjectNav,
    StubuTitle
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