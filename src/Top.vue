<template>
  <div id="top">
    <!-- TODO: v-forにする。href動的に生成する。 -->
    <Tag tagName="this is tag"/>
  </div>
</template>

<script>
import Tag from './components/Tag.vue'

export default {
  name: 'Top',
  components: {
    Tag
  }
}
</script>

<style>

</style>
