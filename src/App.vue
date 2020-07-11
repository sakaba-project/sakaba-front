<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header'
import 'normalize.css'

export default {
  components: {
    Header
  }
}
</script>