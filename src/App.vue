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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  min-height: 100vh;
  font-family: "Alegreya Sans SC", sans-serif;
}

ul li a {
  text-decoration: none;
}

ul {
  list-style-type: none;
}
</style>
