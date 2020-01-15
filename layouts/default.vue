<template>
  <div>
    <div class="line"></div>
    <el-menu
      mode="horizontal"
      background-color="#545c64"
      text-color="#fff"
      active-text-color="#ffd04b">
      <el-menu-item><nuxt-link to="/">Home</nuxt-link></el-menu-item>
      <el-menu-item><nuxt-link to="/mypage">Mypage</nuxt-link></el-menu-item>
      <el-menu-item><nuxt-link to="/login">Login</nuxt-link></el-menu-item>
    </el-menu>
    <el-card>
      <el-container fluid fill-height>
        <nuxt/>
      </el-container>
    </el-card>
  </div>
</template>
