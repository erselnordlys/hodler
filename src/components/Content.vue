<template>
  <div class="content">
    <contentIntro />
    <contentCases />
    <content3 />
  </div>
</template>

<script>
  import contentIntro from "./ContentIntro";
  import contentCases from "./ContentCases";
  import content3 from "./Content3"

    export default {
        name: "content",
      components: {
        contentIntro,
        contentCases,
        content3
      }
    }
</script>

<style scoped>
  .content {
    width: 100%;
  }

</style>
