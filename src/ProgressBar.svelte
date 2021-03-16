<script>
  export let progress;
</script>

<div class="component-container">
  <div class="progress-container">
    <div class="progress-bar" style="width:{progress}%" />
  </div>
</div>

<style>
  .component-container {
    width: 100%;
    align-items: center;
    justify-content: center;
    padding: 10px;
  }
  .progress-container {
    width: 100%;
    border: solid #959595 1px;
    align-items: center;
    justify-content: center;
    height: 30px;
  }
  .progress-bar {
    height: 100%;
    background: rgb(77, 199, 55);
  }
</style>
