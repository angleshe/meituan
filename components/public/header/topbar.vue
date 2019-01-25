<template>
  <div class="topbar">
    <el-row class="cont" align="middle" type="flex">
      <el-col :span="5"><geo></geo></el-col>
      <el-col :span="12"><user></user></el-col>
      <el-col :span="7"><my-nav></my-nav></el-col>
    </el-row>
  </div>
</template>

<style lang="scss" scoped>
.topbar {
  .cont {
    max-width: 1190px;
    margin: 0 auto;
  }
}
</style>

<script>
import Geo from './geo'
import User from './user'
import myNav from './nav'
export default {
  components: {
    Geo,
    User,
    myNav
  }
}
</script>
