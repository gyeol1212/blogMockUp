<template>
  <div id="app" class="mt-0 bg-light">
    <Navbar msg="집 가서 자고 싶다"/>
    <Posts />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Posts from "./components/Posts.vue";

export default {
  components: {
    Navbar,
    Posts
  }
};
</script>

<style scoped>
#app {
  background-color: red;
}
</style>
