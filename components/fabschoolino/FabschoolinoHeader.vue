<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <FabschoolinoTitle></FabschoolinoTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import FabschoolinoTitle from '~/components/fabschoolino/FabschoolinoTitle.vue'

export default {
  components: {
    ProjectNav,
    FabschoolinoTitle
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