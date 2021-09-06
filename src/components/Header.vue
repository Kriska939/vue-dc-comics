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
nav > ul {
  display: flex;
}

nav ul li a {
  color: black;
  padding: 10px;
  font-weight: bold;
  line-height: 80px;
}

header {
  max-width: 1100px;
  margin: 0 auto;
  justify-content: space-between;
  height: 80px;
  margin-bottom: 20px;
}

img {
  max-height: 80px;
}

header img,
header nav {
  margin-top: 10px;
}
</style>