<template>
    <div class="m-3">
        <h3>댓글</h3>
        <ol>
            <Comment v-for="comment in comments" :key="comment.id" :body="comment.body" />
        </ol>
    </div>
</template>

<script>
import Comment from "./Comment.vue";

export default {
  components: {
    Comment
  },
  props: ["comments"]
};
</script>

<style>
</style>
