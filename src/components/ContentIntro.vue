<template>
  <div class="intro">

    <div class="container">
      <div class="left">
        <div class="text">
          React is a "javascript library for building user interfaces" from the fine folks at Facebook & Instagram.
          It strictly focuses on the "V" in your MVC applications, and touts a blazing fast virtual DOM diff implementation.
        </div>
        <!--<button class="cta">CTA button</button>-->
        <a href="#" class="download"></a>
      </div>
      <div class="right"></div>
    </div>

  </div>
</template>

<script>
    export default {
        name: "contentIntro"
    }
</script>

<style scoped>
  .intro {
    display: flex;
    justify-content: center;
    height: 32.2rem;
  }

  .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 50rem;
  }

  .left {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    width: 27rem;
  }

  .text {
    text-align: left;
    margin-bottom: 2.5rem;
  }

  .cta {
    height: 2.2rem;
    width: 9.375rem;
    margin: 1.25rem 0;
    background: #EB5757;
    border-radius: 0.125rem;
    color: #fff;
    cursor: pointer;
    font-size: 1.125rem;
    font-weight: 500;
  }

  .download {
    width: 10.4rem;
    height: 3.45rem;
    background: url("./../assets/logo-gp.png") center/contain no-repeat;
  }

  .right {
    height: 24.75rem;
    width: 14rem;
    background: lightcyan;
  }
</style>
