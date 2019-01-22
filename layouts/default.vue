<template>
  <el-container>
    <el-header>
      <my-header></my-header>
    </el-header>
    <el-main>
      <nuxt/>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<style lang="scss" scoped>
.el-header {
  padding: 0;
}
</style>

<script>
import MyHeader from '@/components/public/header'
export default {
  components: {
    MyHeader
  }
}
</script>

