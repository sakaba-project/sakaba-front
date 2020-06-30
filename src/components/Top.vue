<template>
  <div id="top">
    <!-- TODO: v-forにする。href動的に生成する。 -->
    <h1>Hotタグ</h1>
    <Tag tagName="this is tag"/>
    <h1>声一覧</h1>
    <VoiceCard />
  </div>
</template>

<script>
import Tag from './Tag.vue'
import VoiceCard from './VoiceCard.vue'

export default {
  name: 'Top',
  components: {
    Tag,
    VoiceCard
  }
}
</script>

<style>
  #top {
    margin: 2em;
  }
</style>
