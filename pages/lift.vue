<template>
    <section id="section-wrapper">
      <LiftHeader></LiftHeader>
      <LiftMain></LiftMain>
    </section>
    
</template>

<script>
import LiftHeader from '~/components/lift/LiftHeader.vue'
import LiftMain from '~/components/lift/LiftMain.vue'

export default {
  components: {
    LiftHeader,
    LiftMain
  }
}
</script>

<style>

</style>