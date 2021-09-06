<template>
  <header>
    <figure>
      <img src="@/assets/img/dc-logo.png" alt="Logo DC" />
    </figure>
    <nav>
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
header,
ul {
  display: flex;
  list-style-type: none;
}

ul li a {
  text-decoration: none;
  color: black;
  padding: 10px;
  font-weight: bold;
  line-height: 70px;
}

header {
  justify-content: space-between;
  height: 70px;
  margin: 20px 0;
}

img {
  max-height: 70px;
}
</style>