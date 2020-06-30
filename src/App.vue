<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'

export default {
  components: {
    Header
  }
}
</script>

<style>
    h1 {
    font-size: 1.5em;
    margin-block-start: 0.4em;
    margin-block-end: 0.4em;
    }

    body {
    margin: 0;
    }
</style>