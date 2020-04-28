<template>
    <section id="section-wrapper">
      <Header></Header>
      <Projects></Projects>
      <About></About>
    </section>
    
</template>

<script>
import Header from '~/components/header/Header.vue'
import Projects from '~/components/projects/Projects.vue'
import About from '~/components/about/About.vue'

export default {
  components: {
    Header,
    Projects,
    About
  }
}
</script>

<style>

</style>
