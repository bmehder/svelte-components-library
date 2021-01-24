<svelte:options tag="svelte-button" />

<script>
  import Heading from './Heading.svelte';
  let count = 0;
</script>

<button on:click={() => count++}>{count} + <Heading /></button>

<style>
  button {
    margin: 1em;
    min-width: 100px;
  }
</style>
