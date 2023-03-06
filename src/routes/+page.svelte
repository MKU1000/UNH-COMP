<script>
  import Counter from '../lib/Counter.svelte'
  import unhmLogo from '/logo_unhm.svg'
</script>

<main>
  <div>
    <a href="https://manchester.unh.edu/" target="_blank" rel="noreferrer">
      <img src= {unhmLogo} class="logo svelte" alt ="UNHM Logo"/>
    </a>
  </div>
  <h1>Svelte</h1>

  <div class="card">
    <Counter />
  </div>

</main>

<style>
  .logo {
    height: 6em;
    padding: 1em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }

</style>
