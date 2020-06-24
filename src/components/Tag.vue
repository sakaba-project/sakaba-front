<template>
  <div class="tag">
    <h1>Hotタグ</h1>
    <a href="#" class="btn-icon"><p class="tag-name"># {{ tagName }}</p></a>
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
  border-radius: 50%;
  border-color: #A7A7A7;
  position: relative;
  margin: 2px 4px;
  border: solid 2px #A7A7A7;
}

.tag-name {
  font-size: 16px;
  padding: 8px 8px 8px 8px;
}

.btn-icon:before {
  font-family: "FontAwesome";
  position: absolute;

}

.btn-icon:hover {
  opacity: 0.8;
}
</style>
