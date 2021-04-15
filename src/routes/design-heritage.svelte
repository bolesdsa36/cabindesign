<script>
    import Header1 from "$lib/Header1.svelte";
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Nav />

<Header1 />

<main>
    <section class="section">
        <div class="columns">
            <div class="column">
                <h1 class="has-text-weight-bold">SIZE: 1 x A3 Maximum</h1>
                <p>Pick one of the following Architects to create an A3 poster, read the
                    assessment criteria:</p>
            
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
            <div class="column">
                <img src="images/image4.jpg" alt="random-graphic-designers-clustered" />
            </div>
        </div>
    </section>
   
    
    <h2>Creative Challenge...</h2>
    <p>
        Your presentation should reflect the style of the architect you have
        studied (shapes colours textures etc.).
    </p>

    <h2>Answer...</h2>
    <h3>
        What are the key features of their work?- aesthetic (looks) and
        functional (working)
    </h3>
    <div class="content">
        <ul>
            <li>Include examples of their work and a few notes</li>
        </ul>
    </div>
    <h3>
        What context do they work within?- what cultural/historical/society or
        technological things influence their work?
    </h3>
    <div class="content">
        <ul>
            <li>
                Do they have a design philosophy?- what do they try and do or
                think about design
            </li>
            <li>How long have they been designing?</li>
            <li>What are the main materials their buildings are made from?</li>
            <li>Are there any interesting facts you have found about them?</li>
            <li>Include a quote that they have said</li>
        </ul>
    </div>

    
</main>

<Footer />

<style>
    h2 {
        font-size: 1.5em;
    }
    main {
        padding-left: 1em;
        padding-top: 1em;
        padding-bottom: 1em;
        font-family: "Noto Sans HK", sans-serif;
    }
    h3 {
        color:#f7b1ab;
    }
    p {
        padding-bottom: 1em;
    }
    div{
        font-family: "Noto Sans HK", sans-serif;
    }
</style>
