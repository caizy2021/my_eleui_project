<template>
  <div>
    <el-menu default-active="1" class="el-menu-vertical-demo" mode="vertical" style="width: 200px; text-align:left;">
      <el-menu-item index="1">
        <i class="el-icon-menu"></i>
        首页
      </el-menu-item>
      <el-submenu index="2">
        <span slot="title">
          <i class="el-icon-view"></i>
          我的工作台
        </span>
        <el-menu-item index="2-1">选项1</el-menu-item>
        <el-menu-item index="2-2">选项2</el-menu-item>
        <el-menu-item index="2-3">选项3</el-menu-item>
      </el-submenu>
      <el-menu-item index="3">
        <i class="el-icon-message"></i>
        消息中心
      </el-menu-item>
      <el-menu-item index="4">
        <i class="el-icon-setting"></i>
        个人设置
      </el-menu-item>
    </el-menu>
  </div>
</template>