<template>
  <div id="app">
    <Header />
    <main>
      <Content />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Content,
    Footer,
  },
};
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
</style>
