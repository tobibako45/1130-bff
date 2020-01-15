<template>
  <el-container>
    <el-form>
      <el-button type="primary" @click="loginWithAuthZero">Auth0でログイン
      </el-button>
    </el-form>
  </el-container>

  <!--    <div>-->
  <!--      <button @click="loginWithAuthZero">Auth0でログイン</button>-->
  <!--    </div>-->
</template>

<script>
    export default {
        methods: {
            loginWithAuthZero: function () {
                this.$auth.loginWith('auth0')
            }
        }
    }
</script>
