<script>
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
  import Button from './components/Button.svelte'

  let someColor = 'blue'

</script>

<main>
  <div class="title">
    <div>
      <h1 class="h1">Metztli Development</h1>
      <Button>Hi</Button>
    </div>
  </div>
  <div>
    <a href="https://vitejs.dev" target="_blank"> 
      <img src="/vite.svg" class="logo" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>
  <h1>Vite + Svelte</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>
  .title {
    background-color: rgb(111, 188, 211);
    padding: 2.0rem;
    border-radius: 1.0rem;
    border-color:  rgb(111, 188, 211);
  }
  .title:hover {
    border-color: rgb(70, 68, 208);
  }
  .h1 {
    color: rgb(70, 68, 208)
  }
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }

  .read-the-docs {
    color: #888;
  }
</style>
