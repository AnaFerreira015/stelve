<script>
 let counter = 0
 
 const increment = () => counter += 1
 const decrement = () => counter -= 1
</script>
<style>
  /** Estilo aqui */
</style>
<h1>{ counter }</h1>
<button on:click={ decrement }> Decrement </button>
<button on:click={ increment }> Increment </button>
