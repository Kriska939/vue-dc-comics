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
  flex-basis: calc(100% / 8);
  text-align: center;
  margin-left: 30px;
  height: 300px;
  img {
    width: 150px;
  }

  h3 {
    width: 100%;
    font-size: 16px;
    text-align: left;
  }
}
</style>