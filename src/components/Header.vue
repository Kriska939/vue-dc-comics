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

ul li {
  text-decoration: none;
}

header {
  justify-content: space-between;
}
</style>