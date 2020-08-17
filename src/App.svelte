<style>
  h1 {
    text-transform: uppercase;
    font-size: 3em;
    font-weight: 100;
  }

  main {
    text-align: center;
    height: 100vh;
  }

  p {
    font-size: 1.2em;
  }

  .container {
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    align-content: center;
  }

  .el {
    margin: 5px;
    margin-bottom: 5px;
    background: black;
    color: white;
    font-size: 0.9em;
    width: 180px;
    height: 180px;
    text-align: center;
    text-transform: uppercase;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .el:nth-child(2) {
    background: red;
    height: 200px;
  }
</style>

<script>
  export let name
</script>

<main>
  <h1>Svelte Min</h1>
  <p>
    This is a boilerplate Svelte template. It is designed to quickly spin up an
    Svelte app and begin writing HTML/CSS/JS with the following:
  </p>
  <div class="container">
    <div class="el">Normalize.css</div>
    <div class="el">
      <span>Prettier<br>(and RC file)</span>
    </div>
    <div class="el">
      <span>Flex layout</span>
    </div>
  </div>
  <p>No global stylesheet and no client-side routing.</p>
</main>
