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



</style>
