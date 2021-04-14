<script>
    import Header2 from "$lib/Header2.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Nav />

<Header2 />

<main>
    <section class="section">
        <div class="columns">
            <div class="column">
                <a href="Design-heritage">
                    <img src="images/image10.jpg" alt="graphics-poster1" />
                </a>
            </div>

            <div class="column">
                <h1 class="has-text-weight-bold">1. Perspective</h1>
                <p>
                    Use the box examples on this sheet and create on your own
                    page. Start by putting in a line for the horizon and the
                    VP’s then the front side of each box. Then take the sides
                    back to the vanishing points. If you get stuck draw the
                    example. Place boxes in all different locations and make
                    them different sizes.
                </p>
            </div>
        </div>
    </section>

    <section class="section">
        <div class="columns">
            <div class="column">
                <h1 class="has-text-weight-bold">2. Perspective Bird Houses</h1>
                <p>Draw the bird houses. Add shadows and textures</p>
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
    h1 {
        font-size: 1.5em;
    }
</style>
