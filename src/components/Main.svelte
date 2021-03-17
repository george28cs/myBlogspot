<script>
    /* import Nav from '../components/Nav.svelte';
    import Header from '../components/Header.svelte'; */
    import Sidebar from '../components/Sidebar.svelte';
    export let segment;
</script>

<style>
    .Main-container {
        display: grid;
        grid-template-columns: minmax(100vh, 100vw);
        justify-content: center;
        align-items: center;
        overflow-y: hidden; /* Hide scrollbars */
    }
    .Main-content {
        display: grid;
        grid-template-columns: 1fr 3fr;
        gap: 60px;
        justify-content: space-between;
    }

    .Slot-content {
        padding-top: 2.5em;
        padding-right: 1em;
        height: 90vh;
        width: 97%;
        overflow: scroll;
    }

    ::-webkit-scrollbar {
        -ms-overflow-style: none;  /* IE and Edge */
        scrollbar-width: none;  /* Firefox */
        display: none;
    }
    
</style>

<main class="Main">
    <div class="Main-container">
        <div class="Main-content">
            <Sidebar {segment} />
            <div class="Slot-content">
                <slot />
            </div>
        </div>
    </div>
</main>