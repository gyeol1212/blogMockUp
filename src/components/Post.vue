<template>
	<div class="card container mb-5 px-0">
		<div class="card-header h3 bg-dark text-white mx-0">
			{{ title }}
		</div>
		<div class="card-body">
			<div class="blockquote mb-0">
				<p>{{ body }}</p>
				<p class="small text-right">created at : {{ createdAt }}</p>
			</div>
		</div>
		<Comments :comments="comments"/>
	</div>
</template>

<script>
import Comments from "./Comments.vue";

export default {
  components: {
    Comments
  },
  props: ["title", "body", "createdAt", "comments"]
};
</script>

<style>
</style>
