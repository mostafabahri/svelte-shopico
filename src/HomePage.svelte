<script>
    import StarIcon from "./StarIcon.svelte";

    import Navbar from "./Navbar.svelte";
    import Hero from "./Hero.svelte";
    import HowWorks from "./HowWorks.svelte";

    import Foobar from "./Foobar.svelte";
</script>

<Navbar />

<main class="text-gray-800 mb-40">
    <!-- <Hero /> -->
    <!-- <HowWorks /> -->
    <section id="popular" class="container text-center space-y-12">
        <div>
            <h2 class="text-5xl font-semibold my-16">Popular Items</h2>
            <div class="grid grid-cols-3 gap-6">
                {#each [1, 2, 3] as _}
                    <div class="grid gap-4">
                        <div
                            class="bg-gray-200 rounded-lg grid place-items-center py-10">
                            <img src="holder.js/180x300?theme=sky" alt="" />
                        </div>
                        <div class="flex justify-between">
                            <div>$100</div>
                            <div class="text-teal-400">
                                <StarIcon count={5} />
                            </div>
                        </div>
                        <div>Pottery Vase</div>
                    </div>
                {/each}
                <!-- <div>
                        <img src="" alt="" />
                        <div>$100</div>
                        <div>5 stars</div>
                        <div>Pottery Vase</div>
                    </div>
                    <div>
                        <img src="" alt="" />
                        <div>$100</div>
                        <div>5 stars</div>
                        <div>Pottery Vase</div>
                    </div> -->
            </div>
        </div>

        <button
                class="text-white bg-teal-400 py-3 px-12 rounded-full font-medium">See
                all</button>
        <!-- <Foobar /> -->
    </section>
</main>
