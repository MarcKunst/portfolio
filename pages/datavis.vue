<template>
    <section id="section-wrapper">
      <DatavisHeader></DatavisHeader>
      <DatavisMain></DatavisMain>
    </section>
    
</template>

<script>
import DatavisHeader from '~/components/datavis/DatavisHeader.vue'
import DatavisMain from '~/components/datavis/DatavisMain.vue'

export default {
  components: {
    DatavisHeader,
    DatavisMain
  }
}
</script>

<style>

</style>