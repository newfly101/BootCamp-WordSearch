<script>
    import Router from 'svelte-spa-router';
    import Main from "./pages/Main.svelte";
    import Header from "./components/Header.svelte";
    import Footer from "./components/Footer.svelte";

    const routes = {
        '/': Main,

    }
</script>

<Header />
<main>
    <Router routes={routes} />
</main>
<Footer />
<style>
</style>
