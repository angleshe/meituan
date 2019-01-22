<template>
  <div class="topbar">
    <el-row class="cont">
      <el-col :span="5"><geo></geo></el-col>
      <el-col :span="6"><user></user></el-col>
    </el-row>
  </div>
</template>

<style lang="scss" scoped>
.topbar {
  background-color: #F8F8F8;
  .cont {
    max-width: 1190px;
    margin: 0 auto;
  }
}
</style>

<script>
import Geo from './geo'
import User from './user'
export default {
  components: {
    Geo,
    User
  }
}
</script>
