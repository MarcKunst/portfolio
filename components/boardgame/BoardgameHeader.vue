<template>
    <section id="header-section">
        <ProjectNav></ProjectNav>
        <BoardgameTitle></BoardgameTitle>
    </section>
</template>

<script>
import ProjectNav from '~/components/header/ProjectNav.vue'
import BoardgameTitle from '~/components/boardgame/BoardgameTitle.vue'

export default {
  components: {
    ProjectNav,
    BoardgameTitle
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