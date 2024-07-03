<script lang="ts">
    // import type { LayoutData } from './$types';
    import Navbar from "$lib/Navbar.svelte";
    import Footer from "$lib/Footer.svelte";
    import "../app.css";
    // export let data: LayoutData;
</script>

<Navbar />
<slot />
<Footer />