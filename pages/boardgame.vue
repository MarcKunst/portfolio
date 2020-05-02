<template>
    <section id="section-wrapper">
      <BoardgameHeader></BoardgameHeader>
      <BoardgameMain></BoardgameMain>
    </section>
    
</template>

<script>
import BoardgameHeader from '~/components/boardgame/BoardgameHeader.vue'
import BoardgameMain from '~/components/boardgame/BoardgameMain.vue'

export default {
  components: {
    BoardgameHeader,
    BoardgameMain
  }
}
</script>

<style>

</style>