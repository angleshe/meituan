<template>
  <div class="user">
    <nuxt-link to="./login" class="login">立即登录</nuxt-link>
    <nuxt-link to="./reg" class="reg">注册</nuxt-link>
  </div>
</template>

<style lang="scss" scoped>
.user {
  display: flex;
  align-items: center;
  font-size: 12px;
  .login {
    margin: 0 10px;
  }
  .reg {
    color: #999;
  }
}
</style>
