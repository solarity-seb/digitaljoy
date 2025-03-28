<script>
  export let title = "Welcome to My Site";
  export let subtitle = "Let's build something amazing.";
  export let cta = "Get Started";
  export let ctaLink = "/get-started";
</script>

<section class="hero">
  <div class="container">
    <h1>{title}</h1>
    <p>{subtitle}</p>
    <a class="cta" href={ctaLink}>{cta}</a>
  </div>
</section>

<style>
  .hero {
    padding: 4rem 1rem;
    background: linear-gradient(to right, #1e3a8a, #2563eb); /* blue-ish gradient */
    color: white;
    text-align: center;
  }

  .container {
    max-width: 800px;
    margin: 0 auto;
  }

  h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }

  p {
    font-size: 1.5rem;
    margin-bottom: 2rem;
  }

  .cta {
    background: white;
    color: #1e3a8a;
    padding: 0.75rem 1.5rem;
    border-radius: 0.5rem;
    text-decoration: none;
    font-weight: bold;
  }

  .cta:hover {
    background: #e0e7ff;
  }
</style>
