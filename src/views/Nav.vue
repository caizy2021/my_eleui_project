<template>
  <div>
    <el-menu default-active="1" class="el-menu-demo" mode="horizontal">
      <el-menu-item index="1">首页</el-menu-item>
      <el-submenu index="2">
        <span slot="title">我的工作台</span>
        <el-menu-item index="2-1">选项1</el-menu-item>
        <el-menu-item index="2-2">选项2</el-menu-item>
        <el-menu-item index="2-3">选项3</el-menu-item>
      </el-submenu>
      <el-menu-item index="3">消息中心</el-menu-item>
      <el-menu-item index="4">个人设置</el-menu-item>
    </el-menu>
  </div>
</template>