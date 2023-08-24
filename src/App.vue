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
    <el-main class="content">
      <h1>Welcome to Ada-Copilot</h1>
      <p>Your destination for innovative coding solutions.</p>
    </el-main>
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

.content {
  color: #209748;
  display: block;
  padding: 15rem;
}
</style>