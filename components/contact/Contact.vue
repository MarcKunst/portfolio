<template>
    <section id="project-section">
        <ContactTitle></ContactTitle>
        <ContactContainer></ContactContainer>
    </section>
</template>

<script>
import ContactTitle from '~/components/contact/ContactTitle.vue'
import ContactContainer from '~/components/contact/ContactContainer.vue'

export default {
  components: {
      ContactTitle,
      ContactContainer

  }
}
</script>

<style scoped>

#project-section {
    width: 100%;
    height: 90vh;
    display: grid;
    grid-template-rows: 30% 70%;
    background-color: #323030;
    padding: 4rem 4rem;

}

</style>