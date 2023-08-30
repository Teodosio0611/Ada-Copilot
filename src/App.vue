<template>
    <div class="app">
    <el-header class="header">
      <div class="logo">Ada-Copilot</div>
      <el-menu class="menu" mode="horizontal">
        <el-menu-item index="home">Home</el-menu-item>
        <el-menu-item index="about">About</el-menu-item>
        <el-menu-item index="services">Services</el-menu-item>
        <el-menu-item index="contact">Contact</el-menu-item>
      </el-menu>
    </el-header>

    <div class="searchBox">
    <el-input placeholder="请输入检索关键词" v-model="this.keywords" class="box"></el-input>
    <el-button type="primary" class="button">搜索</el-button>
    </div>
  </div>
</template>


<style>
.app {
  font-family: Arial, sans-serif;
  background-image: url(imgs/cover_11.jpg);
  justify-content: center;
  align-content: center;
  margin: 0 auto;
  height: 100vh;
}

.header {
  background-color: #57c4eb;
  color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  margin: 1rem;
}

.menu {
  background-color: #57c4eb;
}

/* let the searchbox in the center of the page */
.searchBox {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20%;
  height: 10vh;
}


.box {
  width: 70%;
  height: 80%;
  
}

.button {
  width: 10%;
  height: 80%;
}
</style>

<script>
export default {
  data() {
    return {
      keywords: '请输入检索关键词'
    }
  },
}

</script>