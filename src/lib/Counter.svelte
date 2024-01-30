<script>
  let counter = 0;

  function addOne() {
    counter = counter + 1;
  }
</script>

<p>Daudzums: {counter}</p>

<button on:click={addOne}>+1</button>