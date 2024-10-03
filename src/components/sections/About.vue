<template>
  <section id="about">
    <div class="container">
      <div class="about-text">
        <h2 class="section-title">Diddy Party $OIL</h2>
        <p>
          Welcome to the Telegram Diddy Party, where memes meet versus competition! We've launched <span class="highlight">$OIL</span>, a memecoin designed for TikTok's "Diddy Oil Run" game and meme creators worldwide. Whether you're betting on the game or submitting the funniest Diddy Party memes, $OIL rewards your creativity and risk-taking. Our mission is to bring humor, fun, and a new way to engage with TikTok and meme culture, all powered by crypto. 
        </p>
        <p>
          Join the party and become part of a tribe that blends the viral power of memes with innovative digital currency! We're tokenizing the best Diddy Party $OIL memes as Telegram digital assets $OIL holders can sell with no middleman. Join us on our journey to revolutionize the meme economy and explore new possibilities in the world of DeFi!
        </p>
      </div>
      <div class="about-image">
        <img src="../../assets/images/logo.png" alt="About Us Image">
      </div>
    </div>
  </section>
</template>

<script setup>
// No JavaScript logic is required for this static section, but you could use props or external data if needed.
</script>

<style scoped>
#about {
  padding: 4rem 2rem;
  background-color: #c29940; /* Dark background for contrast */
  color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

.section-title {
  font-size: 2.5rem;
  margin-bottom: 2rem;
  color: #FFDD00; /* Neon Green for the section title */
  text-align: center;
}

.about-text {
  font-size: 1.2rem;
  line-height: 1.6;
  text-align: center;
  margin-bottom: 2rem;
}

.about-text p {
  margin-bottom: 1rem;
}

.highlight {
  color: #FFDD00; /* Electric Yellow to highlight important text */
  font-weight: bold;
}

.about-image img {
  width: 100%;
  max-width: 500px;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
}

/* Responsive Design */
@media (min-width: 768px) {
  .container {
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }

  .about-text {
    text-align: left;
    max-width: 50%;
  }

  .about-image {
    max-width: 40%;
  }
}

@media (max-width: 768px) {
  .about-image img {
    margin-bottom: 2rem;
  }
}
</style>
