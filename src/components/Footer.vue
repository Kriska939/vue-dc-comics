<template>
  <footer>
    <div id="top-footer" class="flex">
      <section id="columns" class="container">
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
      <section id="DCHalf">
        <img src="../assets/img/dc-logo-bg.png" alt="DC big logo" />
      </section>
    </div>
    <section id="social">
      <div class="container flex j-between">
        <button>SIGN-UP NOW!</button>
        <div class="flex" id="followContainer">
          <h3>Follow Us</h3>
          <img src="../assets/img/footer-facebook.png" alt="Facebook Logo" />
          <img src="../assets/img/footer-twitter.png" alt="Twitter Logo" />
          <img src="../assets/img/footer-youtube.png" alt="Youtube Logo" />
          <img src="../assets/img/footer-pinterest.png" alt="Pinterest Logo" />
          <img src="../assets/img/footer-periscope.png" alt="Periscope Logo" />
        </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped lang="scss">
@import "@/assets/scss/_vars.scss";
footer {
  background-image: url("../assets/img/footer-bg.jpg");
}
#columns {
  display: flex;
  padding: 50px 0;
  height: 300px;
}
#columns {
  ul {
    margin-right: 30px;
  }
}

#columns {
  ul {
    li {
      font-size: 12px;
    }
  }
}

#columns {
  ul {
    li {
      a {
        color: darkgray;
      }
    }
  }
}

#columns {
  h4 {
    color: white;
    margin-bottom: 5px;
  }
}

#social {
  background-color: $color-gray;
  height: 100px;
  line-height: 100px;
  position: absolute;
  bottom: 0;
  width: 100%;
}

button {
  background-color: transparent;
  border: 2px solid $color-blue;
  padding: 13px;
  color: white;
  font-weight: bold;
  height: 60px;
  margin: 20px 0;
}

#followContainer {
  max-height: 40px;
  h3 {
    color: $color-blue;
    font-size: 24px;
  }
  img {
    margin-top: auto;
    padding-top: 30px;
    padding-left: 10px;
  }
}

#DCHalf {
  img {
    width: 70%;
    height: auto;
    margin-top: -20px;
  }
}
</style>