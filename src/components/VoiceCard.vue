<template>
  <div class="voice-card">
        <p class="voice-card-title">voice title</p>
        <div class="voice-card-tags">
            <Tag tagName="this is tag"/>
        </div>
        <p class="voice-card-message">aaaaaaa</p>
  </div>
</template>

<script>
import Tag from './Tag.vue'

export default {
    name: 'VoiceCard',
    // props: {
    //     title: String
    //     tags: [String]
    //     message: String
    // }
    components: {
        Tag
    }
}
</script>

<style scoped>

.voice-card {
    padding: 0.5em 1em;
    border-radius: 1em;
    border: solid 2px #A7A7A7;
}

.voice-card-title {
  margin: 0.5em 0em 0em;
}

.voice-card-tags {
  margin: 0.5em 0em 0em;
}

.voice-card-message {
  margin: 0.5em 0em 0em;
}
</style>
