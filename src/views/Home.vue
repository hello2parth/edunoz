<template>
  <div>
    <div class="header">
      <div>
        <h1>Where Techies Meets Education</h1>
        <img src="../assets/img/head.jpg" alt="" />
      </div>
    </div>
    Copyright © 2018 Edunoz - All Rights Reserved.
  </div>
</template>

<script>
export default {
  name: "home"
};
</script>
<style lang="less" scoped>
div {
  height: 100%;
  width: 100%;
  overflow: auto;
  display: flex;
  flex-wrap: wrap;
  .header {
    background-image: url("../assets/img/home_bg.jpg");
    height: 697px;
    div {
      display: flex;
      flex-wrap: wrap;
      padding: 0% 5%;
      * {
        margin: auto;
      }
      img {
        width: 50%;
        height: 75%;
      }
      h1 {
        width: 15%;
      }
    }
  }
}
</style>
