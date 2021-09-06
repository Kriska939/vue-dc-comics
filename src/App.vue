<template>
  <div id="app">
    <Header />
    <main>
      <Content />
    </main>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";

export default {
  name: "App",
  components: {
    Header,
    Content,
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

#app {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
