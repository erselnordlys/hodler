<template>
  <div class="cases">

    <div class="container">
      <div class="case case-1">
        <div class="image"></div>
        <div class="description">Case 1 description. What does this case display?</div>
      </div>

      <div class="case case-2">
        <div class="image"></div>
        <div class="description">Case 2 description. What does this case display?</div>
      </div>

      <div class="case case-3">
        <div class="image"></div>
        <div class="description">Case 3 description. What does this case display?</div>
      </div>
    </div>

  </div>
</template>

<script>
    export default {
        name: "contentCases"
    }
</script>

<style scoped>
  .cases {
    display: flex;
    justify-content: center;
    height: 30.2rem;
    background: url("../assets/background.png") center/contain;
  }

  .container {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 50rem;
  }

  .case {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .image {
    height: 7rem;
    width: 7rem;
    border-radius: 50%;
    background: #fff;
  }

  .description {
    width: 10rem;
    margin-top: 2rem;
    color: #fff;
  }
</style>
