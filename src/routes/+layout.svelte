<script>
  import Footer from "../lib/FOOTER.svelte";
  import Header from "../lib/HEADER.svelte";
</script>

<svelte:head>
  <link rel="stylesheet" href="/CSS/main.css">
</svelte:head>


<Header />
<slot />
<Footer />
