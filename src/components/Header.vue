<template>

  <div class="header">
    <div class="title">HODLER</div>

    <div class="buttons">
      <button class="button">What's this?</button>
      <button class="button">Purposes</button>
      <button class="button">Credits</button>
    </div>
  </div>

</template>

<script>
    export default {
        name: "header"
    }
</script>

<style scoped>
  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 5rem;
    width: 50rem;
  }

  .title {
    font-size: 2rem;
  }

  .buttons {
    display: flex;
    justify-content: space-between;
    width: 23rem;
  }

  .button {
    width: 6.23rem;
    height: 2rem;
    background: none;
    border-radius: 0.125rem;
    border: 0.0625rem solid #878787;
    cursor: pointer;
  }
</style>
