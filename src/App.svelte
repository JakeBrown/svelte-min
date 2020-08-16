<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
  }
  .list {
    width: 200px;
    margin-left: auto;
    margin-right: auto;
    display: block;
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

<script>
  export let name
</script>

<main>
  <h1>Hello {name}!</h1>
  <div class="list">
    <p>This is boilerplate with the following configs:</p>
    <ul>
      <li>Normalize.css</li>
    </ul>
  </div>
</main>
