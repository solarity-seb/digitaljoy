<!-- src/lib/Nav.svelte -->
<script>
  import { page } from '$app/stores';
</script>

<nav>
  <a href="/" class:active={$page.url.pathname === '/'}>Home</a>
  <a href="/links" class:active={$page.url.pathname === '/links'}>Links</a>
  <a href="/gallery" class:active={$page.url.pathname === '/gallery'}>Gallery</a>
</nav>

<style>
  nav {
    background: #f0f0f0;
    padding: 1rem;
    display: flex;
    gap: 1rem;
  }

  a {
    text-decoration: none;
    color: #333;
  }

  .active {
    font-weight: bold;
    color: #0070f3;
  }
</style>
