<template>
  <div class="tag">
    <a href="#" class="btn-icon"><p class="tag-name">#{{ tagName }}</p></a>
  </div>
</template>

<script>
export default {
  name: 'Tag',
  props: {
    tagName: String
  }
}
</script>

<style scoped>
.btn-icon {
  display: inline-block;
  max-width: 180px;
  background-color: #FFF;
  color: #7DC097;
  text-decoration: none;
  font-weight: bold;
  border-radius: 3em;
  border: solid 1px #A7A7A7;
  position: relative;
  margin: 2px 4px;
}

.tag-name {
  font-size: 0.5em;
  padding: 1em;
  margin: 0;
}

.btn-icon:before {
  position: absolute;
}

.btn-icon:hover {
  opacity: 0.8;
}
</style>
