<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
  import Nav from '$lib/Nav.svelte'
  import Card from '$lib/Card.svelte'
</script>

<Header />

<Nav />

<main class="content section">
  <h2>SvelteKit</h2>

  <p>Welcome to coding with SvelteKit, a modern JavaScript framework that makes it easy to code great apps.</p>

  <img src="/blueberry.webp" alt="blueberry" />
</main>

<Card />

<Footer />

<style>
  img {
    width: 10cm;
  }
</style>
