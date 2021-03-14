<script>
  import ProgressBar from "./ProgressBar.svelte";
  let progress = 90;
</script>

<ProgressBar {progress} />
<div class="btnContainer">
  <button class="timerBtn">Start Timer</button>
</div>

<style>
  div.btnContainer {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 10px;
    width: 100%;
  }
  button.timerBtn {
    width: 90%;
    height: 4vh;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px;
    color: aliceblue;
    background-color: rgb(236, 56, 56);
    outline-width: 0;
    border: none;
    box-shadow: -4px 4px 0 0 brown;
    transition: ease 1 all;
    cursor: pointer;
  }
  button.timerBtn:hover {
    transform: translate3d(-1px, -1px, 100px);
  }
</style>
