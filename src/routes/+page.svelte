<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Philosophy from "$lib/components/Philosophy.svelte";
  import Services from "$lib/components/Services.svelte";
  import Approach from "$lib/components/Approach.svelte";
  import Leadership from "$lib/components/Leadership.svelte";
  import Contact from "$lib/components/Contact.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="font-sans antialiased text-gray-900 bg-white">
  <Navbar />
  <main>
    <Hero />
    <Philosophy />
    <Services />
    <Approach />
    <Leadership />
    <Contact />
  </main>
  <Footer />
</div>

