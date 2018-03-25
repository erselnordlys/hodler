<template>
    <div class="footer">
      <div class="container">
        <div class="title">Contacts</div>
        <div class="contacts">
          <div class="list">
            <div>Telegram</div>
            <div>Twitter</div>
            <div>Reddit</div>
          </div>

          <div class="list">
            <div class="try">Try</div>
            <a href="#" class="download"></a>
          </div>

        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style lang="less" scoped>
  .footer {
    display: flex;
    justify-content: center;
    height: 15rem;
    width: 100%;
    background: #0ED696;
    color: #fff;
    font-weight: 700;
  }
  .container {
    display: flex;
    align-items: center;
    flex-direction: column;
    width: 50rem;
  }

  .title {
    margin: 1.5rem 0;
    font-size: 1.5rem;
  }

  .contacts {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    text-align: left;

    .list:first-of-type > *  {
      margin-bottom: 1.5rem;
    }
  }

  .list {
    display: flex;
    flex-direction: column;

    &:last-of-type {
      flex-direction: row;
      align-items: center;
    }
  }

  .try {
    background: url("../assets/foreground-logo.svg") no-repeat;
    background-position: right 0;
    background-size: 60%;
    padding: 0.3rem 0 0 0;
    height: 3rem;
    width: 5rem;
    margin-top: 1rem;
    margin-right: 1rem;
    font-size: 1.2rem;
  }

  .download {
    width: 10.4rem;
    height: 3.45rem;
    background: url("./../assets/logo-gp.png") center/contain no-repeat;
  }
</style>
