<template>
  <div class="box">
    <img src="https://colorlib.com/wp/wp-content/uploads/sites/2/HTML5-.jpg" alt="">
    <h4>Powered by Boolean</h4>
  </div>
</template>

<script>
export default {
  name: "Hero"
}
</script>

<style scoped>
  .box {
    position: relative;
    width: 800px;
    height: 500px;
    border: 1px solid black;
    border-radius: 15px;
    overflow: hidden;
  }
  .box img {
    width: 100%;
    height: 100%;
  }

  h4 {
    font-size: 30px;
    position: absolute;
    bottom: 10px;
    left: 10px;
    color: black;
    z-index: 999;
  }
</style>