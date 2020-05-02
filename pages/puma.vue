<template>
    <section id="section-wrapper">
      <PumaHeader></PumaHeader>
      <PumaMain></PumaMain>
    </section>
    
</template>

<script>
import PumaHeader from '~/components/puma/PumaHeader.vue'
import PumaMain from '~/components/puma/PumaMain.vue'

export default {
  components: {
    PumaHeader,
    PumaMain
  }
}
</script>

<style>

</style>