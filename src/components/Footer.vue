<template>
  <footer>
    <section id="columns">
      <ul>
        <h4>DC COMICS</h4>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Video</a></li>
        <li><a href="#">News</a></li>
      </ul>
      <ul>
        <h4>DC COMICS</h4>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">Tv</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Video</a></li>
        <li><a href="#">News</a></li>
      </ul>
      <ul>
        <h4>DC COMICS</h4>
        <li><a href="#">Test</a></li>
        <li><a href="#">Test</a></li>
        <li><a href="#">Test</a></li>
        <li><a href="#">News</a></li>
      </ul>
    </section>
    <section id="social">
      <button>SIGN-UP NOW!</button>
    </section>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
#columns {
  display: flex;
  padding: 50px 0;
  background-image: url("../assets/img/footer-bg.jpg");
}
#columns ul {
  margin-right: 30px;
}

#columns ul li {
  font-size: 12px;
}

#columns ul li a {
  color: darkgray;
}

#columns h4 {
  color: white;
  margin-bottom: 5px;
}

#social {
  background-color: rgb(82, 82, 82);
  height: 150px;
  line-height: 150px;
}

button {
  background-color: transparent;
  border: 2px solid dodgerblue;
  padding: 13px;
  color: white;
  font-size: bold;
}
</style>