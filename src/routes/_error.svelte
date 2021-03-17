<script>
	export let status;
	const dev = process.env.NODE_ENV === 'development';
</script>

<style>
	.Error404{
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.Error404-image figure{
		margin: 0;
		padding: 0;
		text-align: right;
	}

	.Error404 img {
		width: 300px;
		margin: 2em 0;
	}

</style>

<svelte:head>
	<title>{status}</title>
</svelte:head>

<div class="Error404">
	<!-- <div class="Error404-message">
		<h1>{status}</h1>
		<p>{error.message}</p>
		{#if dev && error.stack}
			<pre>{error.stack}</pre>
		{/if}
	</div> -->
	<div class="Error404-image">
		<figure>
			<img src="images/404.gif" alt="error 404">
		</figure>
	</div>
</div>

