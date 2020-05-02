<template>
    <section id="section-wrapper">
      <StubuHeader></StubuHeader>
      <StubuMain></StubuMain>
    </section>
    
</template>

<script>
import StubuHeader from '~/components/stubu/StubuHeader.vue'
import StubuMain from '~/components/stubu/StubuMain.vue'

export default {
  components: {
    StubuHeader,
    StubuMain
  }
}
</script>

<style>

</style>