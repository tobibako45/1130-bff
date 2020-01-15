<template>
  <el-container>
    <h1>Hello, {{this.$auth.$state.user.family_name}}</h1>
  </el-container>
</template>

<script>
    export default {
        middleware: 'auth'
    }
</script>
