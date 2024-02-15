<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
  import Nav from '$lib/Nav.svelte'
  import Image from '../../lib/Image.svelte'
</script>

<Header title="About me " subtitle="I am cool" />
<Nav />
<main class="content section">
  <h2 class="title">My summer activities</h2>
  <div class="columns">
    <div class="column">
      <h3>Summer activity 1</h3>
      <p>I went to lake benmore over the holidays with my grandparents, my mum, and my sister where i went water skiing and biscuiting.</p>
      <Image src="skiing.jpg" alt="me water skiing " caption="Me water skiing "></Image>
    </div>

    <div class="column">
      <h3>Summer activity 2</h3>
      <p>over new years i stated with my friend in twizel where we went shopping and biscuiting</p>
      <Image src="friends.jpg" alt="four girls" caption="me and my friends at lake twizel"></Image>
    </div>
    <div class="column">
      <h3>Summer activity 3</h3>
      <p>i went to lake hood with andra on a scorching hot day where we almost died of heat but we could not swim because the lake was gross</p>
      <Image src="lakehood.jpg" alt="picture of lake " caption="lake hood"></Image>
    </div>
  </div>
</main>
<Footer />

<style>
  h2 {
    text-align: center;
  }
</style>
