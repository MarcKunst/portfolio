<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <AnimationTitle></AnimationTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import AnimationTitle from '~/components/animation/AnimationTitle.vue'

export default {
  components: {
    ProjectNav,
    AnimationTitle
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