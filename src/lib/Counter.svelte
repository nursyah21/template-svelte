<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  count is <span class="border px-3 py-0 bg-gray-500 text-white">
    {count}
  </span> 
</button>
