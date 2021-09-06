<template>
  <header class="container">
    <figure>
      <img src="@/assets/img/dc-logo.png" alt="Logo DC" class="logo" />
    </figure>
    <nav>
      <ul>
        <li v-for="(link, index) in navlinks" :key="index">
          <a href="#">{{ link.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navlinks: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
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
  justify-content: space-between;
  height: 100px;
}

.logo {
  max-height: 80px;
  margin-bottom: 20px;
}

header img,
header nav {
  margin-top: 10px;
}
</style>