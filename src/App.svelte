<script>
  import HowTo from "./HowTo.svelte";
  import Timer from "./Timer.svelte";
</script>

<div class="app">
  <h1>Hand Washing App</h1>
  <Timer />
  <HowTo />
</div>

<style>
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    padding: 10px;
  }

  .app h1 {
    align-items: flex-start;
    padding: 10px;
    font-size: 3rem;
    font-weight: 500;
  }
</style>
