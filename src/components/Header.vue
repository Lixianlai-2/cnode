<template>
  <div class="header">
    <img src="../assets/cnodejs_light.svg" alt="cnode标志" />
    <ul>
      <li><a href="#">首页</a></li>
      <li><a href="#">新手入门</a></li>
      <li><a href="#">API</a></li>
      <li><a href="#">关于</a></li>
      <li><a href="#">注册</a></li>
      <li><a href="#">登录</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  display: flex;
  /* border: 3px solid red; */
  background: #5a5555;
  justify-content: space-between;
}

img {
  width: 100px;
  padding: 10px;
}

ul {
  padding-left: 100px;
}

li {
  display: inline-block;
  padding-right: 20px;
}

a {
  color: #cccccc;
}
</style>
