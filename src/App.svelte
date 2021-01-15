<script>
    export let name;
</script>

<main>
    <h1>Hello {name}!</h1>
    <div>
        hello
    </div>
    <p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style type="text/scss" global>
  $color: red;

  h1 {
    color: $color;
  }

  div {
    background: green;

    > p {
      color: #fff;
    }
  }


  body {
    background: red;
  }

</style>