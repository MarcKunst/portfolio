<template>
    <section>
        <ProjectsTitle></ProjectsTitle>
    </section>
</template>

<script>
import ProjectsTitle from '~/components/projects/ProjectsTitle.vue'

export default {
  components: {
      ProjectsTitle
  }
}
</script>

<style scoped>

section {
    width: 100%;
    height: 100vh;
    background-color: #fdfdfd;
    display: flex;
    justify-content: center;
    padding: 2rem;

}

</style>