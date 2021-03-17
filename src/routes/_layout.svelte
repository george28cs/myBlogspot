<script>
	import Main from '../components/Main.svelte';
	export let segment;
</script>

<Main {segment}>
	<slot></slot>
</Main>