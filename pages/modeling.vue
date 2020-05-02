<template>
    <section id="section-wrapper">
      <ModelingHeader></ModelingHeader>
      <ModelingMain></ModelingMain>
    </section>
    
</template>

<script>
import ModelingHeader from '~/components/modeling/ModelingHeader.vue'
import ModelingMain from '~/components/modeling/ModelingMain.vue'

export default {
  components: {
    ModelingHeader,
    ModelingMain
  }
}
</script>

<style>

</style>