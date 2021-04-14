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
                <div class="content">
                    <ul>
                        <li>Mies Van der Rohe</li>
                        <li>Zaha Hadid</li>
                        <li>Frank Gehery</li>
                        <li>Le Cobuisier</li>
                        <li>Frank Lloyd Wright</li>
                        <li>Daniel Libeskind</li>
                    </ul>
                    </div>
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
    <section class="section">
        <div class="columns">
            <div class="column">
                <h1 class="has-text-weight-bold">3. Scale</h1>
                <p>Draw the bird houses. Add shadows and textures</p>
            </div>
            <div class="column">
                <p></p>
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
