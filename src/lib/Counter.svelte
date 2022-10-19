<script>
  let count = 0
  const increment = () => {
    count += 1
    window.alert('I wanna see you dance mate!')
  }
</script>

<button on:click={increment}>
  count is {count}
</button>
