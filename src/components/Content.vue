<template>
  <div class="content">
    <contentIntro />
    <contentCases />
  </div>
</template>

<script>
  import contentIntro from "./ContentIntro";
  import contentCases from "./contentCases";

    export default {
        name: "content",
      components: {
        contentIntro,
        contentCases
      }
    }
</script>

<style scoped>
  .content {
    width: 100%;
  }

</style>
