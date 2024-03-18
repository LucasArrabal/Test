<script lang="ts">
    let count = 0;
</script>

<h1>Counter: {count}</h1>
<button on:click={() => count--}>Menos</button>
<button on:click={() => count++}>Mais</button>
<button on:click={() => count = 0}>Limpar</button>