<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Nav />

<Header />

<main>
    <section class="section">
        <div class="columns">
            <div class="column">
                <a href="Design-heritage">
                    <img src="images/image12.jpg" alt="graphics-poster" />
                </a>
            </div>

            <div class="column">
                <h1 class="has-text-weight-bold">Design Heritage</h1>
                <p>
                    Click on the image to the left which will redirect you to
                    the Design Heritage Page. You will need to complete all
                    tasks to be able to advance to the next section. Please
                    complete all tasks to a high standard.
                </p>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="columns">
            <div class="column">
                <h1 class="has-text-weight-bold">Visual Communication</h1>
                <p>
                    Click on the image to the right which will redirect you to
                    the Visual Communications Page. You will need to complete
                    all tasks to be able to advance to the next section. Please
                    complete all tasks to a high standard.
                </p>
            </div>
            <div class="column">
                <a href="visual-communication">
                    <img src="images/image8.jpg" alt="birds-house-poster" />
                </a>
            </div>
        </div>
    </section>
</main>

<Footer />

<style>
    p {
        font-family: "Noto Sans HK", sans-serif;
        font-size: 1em;
    }
</style>
