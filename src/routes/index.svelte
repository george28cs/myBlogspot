<script context="module">
	export function preload() {
		return this.fetch(`blog.json`).then(r => r.json()).then(posts => {
			return { posts };
		});
	}
</script>

<script>
	import Post from '../components/Post.svelte';
	export let posts;
</script>

<style>
	.Post {
		display: grid;
		justify-content: space-between;
		gap: 15px;
		grid-template-columns: 1fr;
	}
</style>

<svelte:head>
	<title>Jorge Carrión</title>
</svelte:head>

<meta name="description" content ="Blog de Jorge Carrión">

<div class="Home">
	<div class="Post">
		{#each posts as post}
			<Post {post}/>
		{/each}
	</div>
</div>