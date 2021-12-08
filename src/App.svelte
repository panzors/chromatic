<script>
  import Header from "./components/Header.svelte";
  import NavBar from "./components/NavBar.svelte";
  import Performance from "./components/Performance.svelte";
</script>

<Header />

<main>
  <NavBar />
  <div class="content">
    <Performance />
  </div>
</main>

<style>
  .content {
  }
  main {
    display: flex;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
