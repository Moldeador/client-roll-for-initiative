<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import batLogo from './assets/Edouard-Joseph-dAlton-bat.jpg'
  import Counter from './lib/Counter.svelte'
  import CreateRoom from './lib/CreateRoom.svelte';
</script>

<main>
  <div>
    <a href="https://www.dmsguild.com/browse.php?author=Santiago%20Cabrera" target="_blank" rel="noreferrer">
      <img src={batLogo} class="logo" alt="An illustration by Edouard Joseph d’Alton of a bat's squeleton" />
    </a>
  </div>
  <h1>Goblin 𓃛 Thermomancer</h1>

  <div class="card">
    <CreateRoom />
  </div>

  <div class="card">
    <Counter />
  </div>
</main>

<style>
  .logo {
    height: 30em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #a50a0aaa);
  }
</style>
