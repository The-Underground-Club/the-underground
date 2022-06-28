<script>
  import Header from "./assets/header.svelte";
  import Body from "./assets/body.svelte";
  import About from "./assets/about.svelte";
  import Footer from "./assets/footer.svelte";
</script>

<Header />
<main class="bg-neutral-500 text-neutral-700">
  <Body />
  <hr class="h-1 rounded bg-neutral-800 border-0 mx-10" />
  <About />
</main>
<Footer />
