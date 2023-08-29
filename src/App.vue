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
  height: 120vh;
  background-image: url(imgs/background.png);
}

.header {
  background-color: #d33788;
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
  background-color: #d33788;
}

.searchBox {
  margin-top: 60px;
  display: flex;
  padding: 15rem;
  height: 60px;
  margin-left: 100px;
  
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