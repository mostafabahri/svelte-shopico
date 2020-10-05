<script>
    import Hero from "./Hero.svelte";
    import Navbar from "./Navbar.svelte";

    import Foobar from "./Foobar.svelte";
</script>

<style>
    :global(.container) {
        @apply max-w-6xl;
        @apply mx-auto;
        @apply px-2;
    }
</style>

<Navbar />

<main>
    <Hero />
    <!-- <Foobar /> -->
</main>
