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
                <a href="design-heritage">
                    <img src="images/image12.jpg" alt="graphics-poster"/>
                </a>
            </div>
            
            <div class="column">
            <p>
                Click on the image to the left which will redirect you to the
                Design Heritage Page. You will need to complete all tasks to be
                able to advance to the next section. Please complete all tasks
                to a high standard.
            </p>
        </div>
    </section>

    <section class="section">
        <div class="columns">
            <div class="column">
                <p>
                    Click on the image to the right which will redirect you to the
                    Visual Communications Page. You will need to complete all tasks to be
                    able to advance to the next section. Please complete all tasks
                    to a high standard.
                </p>
            </div>
            <div class="column">
                <a href="visual-communication">
                    <img src="images/image8.jpg" alt="birds-house-poster"/>
                </a>
            </div>
            
            
        </div>
    </section>

    <progress class="progress" value="15" max="100">15%</progress>
</main>

<Footer />
