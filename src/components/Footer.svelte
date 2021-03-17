<script>
    const date = new Date();
    const year = date.getFullYear();
</script>

<style>
    .Footer-content {
        color: #ccc;
        font-size: 12px;
        border-bottom: 1px solid rgba(255,62,0,0.1);
		font-weight: 300;
		padding: 0.3em 1em;
    }

    .Footer-svelte a {
        color: rgb(255,62,0);
        text-decoration: none;
        font-weight: bold;
    }
</style>

<footer class="Footer">
<div class="Footer-container">
    <div class="Footer-content">
        <div class="Footer-copy">
            Jorge Carrión {year}
        </div>
        <div class="Footer-svelte">
             Powered by <a target="_blank" href="https://svelte.dev/">Svelte</a>
        </div>
    </div>
</div>
</footer>