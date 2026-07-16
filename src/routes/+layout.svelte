<script lang="ts">
  import "$lib/global.css"
	import favicon from "$lib/assets/favicon.svg";

  import Footer from "$lib/components/Footer.svelte";
  import Navbar from "$lib/components/Navbar.svelte";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<Navbar />

{@render children()}

<Footer />
