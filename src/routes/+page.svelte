<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Stats from "$lib/components/Stats.svelte";
  import Platform from "$lib/components/Platform.svelte";
  import Testimonials from "$lib/components/Testimonials.svelte";
  import TeamSmart from "$lib/components/TeamSmart.svelte";
  import Adoption from "$lib/components/Adoption.svelte";
  import Integrations from "$lib/components/Integrations.svelte";
  import Models from "$lib/components/Models.svelte";
  import TrustedBy from "$lib/components/TrustedBy.svelte";
  import Pricing from "$lib/components/Pricing.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="bg-black min-h-screen text-white font-sans selection:bg-blue-500/30">
  <Navbar />
  
  <main>
    <Hero />
    <Stats />
    <Platform />
    <Testimonials />
    <TeamSmart />
    <Adoption />
    <Integrations />
    <Models />
    <TrustedBy />
    <Pricing />
  </main>

  <Footer />
</div>

