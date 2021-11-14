<script>
    export let name;
</script>

<main>
  <section>
    <h1>Hello {name}!</h1>
    <p>
      This template is created to compile your awesome Svelte code to one single HTML file.
    </p>
    
    <p>
      Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
      how to build Svelte apps.
    </p>
  </section>
</main>

<style>

  main {
    width: 100%;
    height: 100vh;
    display: grid;
    place-items: center;
  }

  section {
    text-align: center;
  }

  section h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
  }
  
  section p {
    margin: 0.5rem 0;
  }

  section p:first-child {
    margin-top: 5rem;
  }
</style>
