<template>
  <div class="app">
    <Header />
    <Content />
    <Footer />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Header from "./components/Header";
import Content from "./components/Content";
import Footer from "./components/Footer";

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    Content,
    Footer
  }
}
</script>

<style>
  body {
    margin: 0;
  }
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>
