<template>
    <section id="section-wrapper">
      <PipHeader></PipHeader>
      <PipMain></PipMain>
    </section>
    
</template>

<script>
import PipHeader from '~/components/pip/PipHeader.vue'
import PipMain from '~/components/pip/PipMain.vue'

export default {
  components: {
    PipHeader,
    PipMain
  }
}
</script>

<style>

</style>