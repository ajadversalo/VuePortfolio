<template>
  <div class="w-max">
    <div class="text-5xl w-100">
      {{ name }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'NameHeader',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
