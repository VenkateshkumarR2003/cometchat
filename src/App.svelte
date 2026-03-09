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


<svelte:head>
<title>AI Agent Platform | CometChat</title>

<meta name="description"
content="Build AI-powered chat experiences with CometChat. Add messaging, voice and video to your applications." />

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta property="og:title" content="AI Agent Platform | CometChat">
<meta property="og:description" content="Build AI-powered chat experiences with CometChat.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://cometchatclone.netlify.app/">

<link rel="canonical" href="https://cometchatclone.netlify.app/" />

<script type="application/ld+json">
{
 "@context": "https://schema.org",
 "@type": "WebSite",
 "name": "CometChat Clone",
 "url": "https://cometchatclone.netlify.app/"
}
</script>
</svelte:head>

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