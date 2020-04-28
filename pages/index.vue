<template>
    <section id="section-wrapper">
      <Header></Header>
      <Projects></Projects>
      <About></About>
      <Contact></Contact>
    </section>
    
</template>

<script>
import Header from '~/components/header/Header.vue'
import Projects from '~/components/projects/Projects.vue'
import About from '~/components/about/About.vue'
import Contact from '~/components/contact/Contact.vue'

export default {
  components: {
    Header,
    Projects,
    About,
    Contact
  }
}
</script>

<style>

</style>
