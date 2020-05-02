<template>
    <section id="section-wrapper">
      <AnimationHeader></AnimationHeader>
      <AnimationMain></AnimationMain>
    </section>
    
</template>

<script>
import AnimationHeader from '~/components/animation/AnimationHeader.vue'
import AnimationMain from '~/components/animation/AnimationMain.vue'

export default {
  components: {
    AnimationHeader,
    AnimationMain
  }
}
</script>

<style>

</style>