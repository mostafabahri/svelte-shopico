<script>
    import PromoCollection from "./PromoCollection.svelte";

    import Navbar from "./Navbar.svelte";
    import Hero from "./Hero.svelte";
    import HowWorks from "./HowWorks.svelte";
    import PopularItems from "./PopularItems.svelte";
    import KeyFeatures from "./KeyFeatures.svelte";
</script>

<style>
</style>

<Navbar />

<main class="text-gray-800 mb-40">
    <Hero />
    <HowWorks />
    <PopularItems />
    <KeyFeatures />

    <PromoCollection />
</main>
