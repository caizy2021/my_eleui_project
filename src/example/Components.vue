<template>
  <div>
    <el-container class="container">
      <!-- 头部 -->
      <el-header class="header">

        <el-menu default-active="2" class="el-menu-demo" mode="horizontal">
          <el-menu-item>
            <img src="../assets/logo.svg" alt="">
          </el-menu-item>
          <el-menu-item index="1">指南</el-menu-item>
          <el-menu-item index="2">组件</el-menu-item>
          <el-menu-item index="3">主题</el-menu-item>
          <el-menu-item index="4">资源</el-menu-item>
        </el-menu>

      </el-header>
      <el-container>
        <!-- 侧边栏导航 -->
        <el-aside class="aside" width="200px">

          <el-menu router="true" default-active="1" class="el-menu-vertical-demo" mode="vertical">
            <el-menu-item index="/components/container">
              <i class="el-icon-menu"></i>
              Container布局
            </el-menu-item>
            <el-menu-item index="/components/element">
              <i class="el-icon-menu"></i>
              Element布局
            </el-menu-item>
            <el-menu-item index="/components/icon">
              <i class="el-icon-menu"></i>
              Icon图标库
            </el-menu-item>
          </el-menu>

        </el-aside>
        <!-- 内容 -->
        <el-main class="main">
          <router-view></router-view>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>
<style scoped>
.container{
  position: fixed;
  top: 0; left: 0; right: 0; bottom: 0;
}
.aside{
  text-align: left;
  position: absolute;
  top: 61px; left: 0; bottom: 0;
}
.main{
  text-align: left;
  position: absolute;
  top: 61px; left: 206px; bottom: 0; right: 0;
}
.el-menu{
  height: 100%;
}
</style>