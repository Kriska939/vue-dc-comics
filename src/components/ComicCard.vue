<template>
  <div class="comic">
    <img :src="comic.thumb" :alt="comic.series" />
    <h3>{{ comic.series }}</h3>
  </div>
</template>

<script>
export default {
  name: "ComicCard",
  props: ["comic"],
};
</script>

<style scoped lang="scss">
.comic {
  max-width: calc(100% / 6);
  text-align: center;
  margin-left: 30px;
  img {
    width: 100%;
    height: auto;
  }

  h3 {
    width: 100%;
    font-size: 16px;
    text-align: left;
  }
}
</style>