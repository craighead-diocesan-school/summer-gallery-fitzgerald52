<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
  import Nav from '$lib/Nav.svelte'
</script>

<Header />
<Nav />
<main class="content section">
  <h2 class="title">My summer activities</h2>
  <div class="columns">
    <div class="column">
      <h3>Summer activity 1</h3>
      <p>fjdshgviojvafpsjvodjv</p>
    </div>

    <div class="column">
      <h3>Summer activity 2</h3>
      <p>fjdshgviojvafpsjvodjv</p>
    </div>
    <div class="column">
      <h3>Summer activity 3</h3>
      <p>fjdshgviojvafpsjvodjv</p>
    </div>
  </div>
</main>
<Footer />

<style>
  h2 {
    text-align: center;
  }
</style>
