<template>
    <section id="project-section">
        <ProjectsTitle></ProjectsTitle>
        <ProjectContainer></ProjectContainer>
    </section>
</template>

<script>
import ProjectsTitle from '~/components/projects/ProjectsTitle.vue'
import ProjectContainer from '~/components/projects/ProjectContainer.vue'

export default {
  components: {
      ProjectsTitle,
      ProjectContainer
  }
}
</script>

<style scoped>

#project-section {
    width: 100%;
    height: 200vh;
    background-color: #fdfdfd;
    display: grid;
    grid-template-rows: 20% 80%;
    padding: 4rem 4rem;
    background-image: url(../../assets/images/project-bg.png);
    background-position: bottom;
    background-size: contain;
    background-repeat: no-repeat;

}

</style>