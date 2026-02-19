<script lang="ts">
  import Sidebar from "$lib/components/Sidebar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Content from "$lib/components/Content.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="flex min-h-screen bg-black font-sans">
  <Sidebar />
  <main class="flex-1 ml-16 relative">
    <Hero />
    <Content />
    <Footer />
  </main>
</div>

