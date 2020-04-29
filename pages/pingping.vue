<template>
    <section id="section-wrapper">
      <PingPingHeader></PingPingHeader>
      <PingPingMain></PingPingMain>
    </section>
    
</template>

<script>
import PingPingHeader from '~/components/pingping/PingPingHeader.vue'
import PingPingMain from '~/components/pingping/PingPingMain.vue'

export default {
  components: {
    PingPingHeader,
    PingPingMain
  }
}
</script>

<style>

</style>