<script>
  import Navbar from "./components/Navbar.svelte";
  import Hero from "./components/Hero.svelte";
  import AgentFeature from "./components/AgentFeature.svelte";
  import Trusted from "./components/Trusted.svelte";
  import Features from "./components/Features.svelte";
  import ChatUI from "./components/ChatUI.svelte";
  import Notifications from "./components/Notifications.svelte";
  import Insights from "./components/Insights.svelte";
  import TechSection from "./components/TechSection.svelte";
  import AgentOptions from "./components/AgentOptions.svelte";
  import IntegrationOptions from "./components/IntegrationOptions.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<div class="page">

  <!-- Header -->
  <header>
    <Navbar />
  </header>

  <!-- Main Content -->
  <main>

    <section>
      <Hero />
    </section>

    <section>
      <Trusted />
    </section>

    <section>
      <AgentFeature />
    </section>

    <section>
      <Features />
    </section>

    <section>
      <ChatUI />
    </section>

    <section>
      <Notifications />
    </section>

    <section>
      <Insights />
    </section>

    <section>
      <TechSection />
    </section>

    <section>
      <AgentOptions />
    </section>

    <section>
      <IntegrationOptions />
    </section>

  </main>

  <!-- Footer -->
  <footer>
    <Footer />
  </footer>

</div>

<style>

.page{
  min-height:100vh;
  font-family:'Satoshi', sans-serif;
  color:white;
  background:#0A0914;
}

main{
  display:flex;
  flex-direction:column;
}

</style>