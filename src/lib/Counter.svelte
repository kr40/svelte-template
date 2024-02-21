<script>
  let count = 0;
  const increment = () => {
    count++;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>
