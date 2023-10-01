<script>
  import { onMount } from 'svelte';

  onMount(async () => {
    const { createGlobe } = await import('$lib/globe.js');
    createGlobe();
  }); 
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
