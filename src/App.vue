<template>
  <div id="app">
    <div class="header">
      <div class="container">
        <div class="header_left">
          <h2>FITNESS CLUB</h2>
        </div>
        <div class="header_right">
          <div class="header_btn">
            <a class="right_btn" href="#">DEMOS</a>
            <a class="right_btn" href="#">SHOP</a>
            <a class="right_btn" href="#">ELEMENTS</a>
            <a class="right_btn" href="#">PAGES</a>
            <a class="right_btn" href="#">FEATURES</a>
            <a class="right_btn" href="#">BLOG</a>
            <a class="right_btn" href="#">PORTFOLIOS</a>
          </div>
        </div>
      </div>
    </div>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld";

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="css">
#app {
  position: absolute;
  top: 0;
  left: 0;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  width: 100%;
}

.header {
  height: 65px;
  margin: 0 0 0 0;
  background-color: rgba(49, 52, 64, 0.99);
}

.header_left {
  position: absolute;
  margin-left: 30px;
  color: #fff;
}

.header_right {
  margin-top: 22px;
  float: right;
  margin-right: 30px;
}

.header_btn {
  position: relative;
  margin-left: 100px;
}

.right_btn {
  width: 120px;
  background: none;
  border: none;
  color: #fff;
  font-size: 20px;
  text-decoration: none;
  transition: 0.5s;
}

.header_btn a {
  margin-right: 15px;
}

.right_btn:hover {
  color: #FFB700FF;
  transition-duration: 1s;
}

@media (max-width: 960px) {
  .header{
    max-width: 960px;
    height: 70px;
    display: block;
    justify-content: center;
    text-align: center;
  }

  .header_right {
    position: relative;
    top: 20px;
    left: 32px;
  }

  .header_left {
    justify-content: center;
  }
}


@media (max-width: 767px)
{
  .header{
    max-width: 767px;
    height: 70px;
    display: block;
    justify-content: center;
    text-align: center;
  }

  .header_right {
    position: relative;
    top: 20px;
    left: 32px;
  }

  .header_left {
    position: absolute;
    left: 170px;
    top: -10px;
  }

  .right_btn {
    font-size: 18px;
  }

  .header_btn a{
    margin-right: 6px;
  }
}

@media (max-width: 576px) {
  .header_left {
    left: 70px;
    top: 3px;
  }

  h2 {
    font-size: 18px;
  }

  .header_right {
    left: 28px;
    position: relative;

  }

  .right_btn {
    font-size: 9px;
  }

  .header_btn a{
    margin-right: 6px;
  }
}

</style>
