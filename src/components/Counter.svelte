<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment} class="bg-gradient-to-r from-cyan-500 to-blue-500 text-white p-5 rounded-full">
  count is {count}
</button>
