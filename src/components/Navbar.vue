<template>
  <nav class="navbar sticky-top navbar-light bg-dark h2 p-3 text-white">
    {{ msg }}
  </nav>
</template>

<script>
export default {
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
