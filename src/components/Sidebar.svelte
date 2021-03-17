<script>
    import Nav from '../components/Nav.svelte';
    import Header from '../components/Header.svelte';
    import Footer from '../components/Footer.svelte';
    export let segment;
</script>

<style>
     .Sidebar {
        height: 100vh;
        background-color: #2b2b2b;
        text-align: center;
    }
    .Sidebar-container {
        padding-top: 75px;
    }
</style>

<div class="Sidebar">
    <div class="Sidebar-container">
        <Header />
        <Nav {segment}/>
        <Footer />
    </div>
</div>