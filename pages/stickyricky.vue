<template>
    <section id="section-wrapper">
      <StickyrickyHeader></StickyrickyHeader>
      <StickyrickyMain></StickyrickyMain>
    </section>
    
</template>

<script>
import StickyrickyHeader from '~/components/stickyricky/StickyrickyHeader.vue'
import StickyrickyMain from '~/components/stickyricky/StickyrickyMain.vue'

export default {
  components: {
    StickyrickyHeader,
    StickyrickyMain
  }
}
</script>

<style>

</style>