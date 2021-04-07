<script>
	import Header from "$lib/Header.svelte";
	import Nav from "$lib/Nav.svelte";
	import Footer from "$lib/Footer.svelte";

</script>

<Nav />

<Header />



<main>
dfghjk
</main>


<Footer />

<style>
		/* LAYOUT */
  :global(Header) { grid-area: h; }
  :global(Nav)    { grid-area: n; }
  :global(main)   { grid-area: m; }
  :global(Footer) { grid-area: f; }

  :global(#svelte) {
    display: grid;
    grid: " n   n   " auto
          " h   h   " auto
          " m   m   " auto
          " f   f   " auto
          / 1fr 3fr ;
  }

</style>

