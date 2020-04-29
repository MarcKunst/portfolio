<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <PingPingTitle></PingPingTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import PingPingTitle from '~/components/pingping/PingPingTitle.vue'

export default {
  components: {
    ProjectNav,
    PingPingTitle
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