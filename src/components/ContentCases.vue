<template>
  <div class="cases">

    <div class="container">
      <div class="left">
        <div class="text">
          React is a "javascript library for building user interfaces" from the fine folks at Facebook & Instagram.
          It strictly focuses on the "V" in your MVC applications, and touts a blazing fast virtual DOM diff implementation.
        </div>
        <button class="cta">CTA button</button>
        <a href="#" class="download"></a>
      </div>
      <div class="right"></div>
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
    height: 32.2rem;
    background: #0ED696;
  }

  .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 50rem;
  }
</style>
