<script>
	export let segment;
</script>

<style>
	nav {
		border-bottom: 1px solid rgba(255,62,0,0.1);
		font-weight: 300;
		padding: 0 1em 6em;
	}

	ul {
		margin: 0;
		padding: 0;
	}

	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
	}

	li a:hover {
		color: rgba(10, 183, 206, 0.89);
	}

	[aria-current] {
		position: relative;
		display: inline-block;
	}

	[aria-current]::after {
		position: absolute;
		content: '';
		width: calc(100% - 1em);
		height: 2px;
		background-color: rgb(255,62,0);
		display: block;
		bottom: -1px;
	}

	a {
		text-decoration: none;
		padding: 0.5em 0.5em;
		display: block;
		color: #ccc;
	}
</style>

<nav>
	<ul>
		<li><a aria-current="{segment === undefined ? 'page' : undefined}" href=".">Home</a></li>
		<li><a aria-current="{segment === 'about' ? 'page' : undefined}" href="about">Acerca de mi</a></li>
		<li><a aria-current="{segment === 'contact' ? 'page': undefined}" href="contact">Contacto</a></li>
		<li><a aria-current="{segment === 'general' ? 'page': undefined}" href="general">General</a></li>
		<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">Blog</a></li>
		<li><a aria-current="{segment === 'newsletter' ? 'page': undefined}" href="newsletter">Newsletter</a></li>
	</ul>
</nav>
