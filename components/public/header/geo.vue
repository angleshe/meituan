<template>
  <div class="geo">
    <div class="city"><i class="el-icon-location"></i>大厂回族自治区</div>
    <nuxt-link to="./chooseCity" class="choose-btn">切换城市</nuxt-link>
    <div class="city-list">[三河 香河 廊坊]</div>
  </div>
</template>

<style lang="scss" scoped>
.geo {
  display: flex;
  align-items: center;
  font-size: 12px;
  color: $subtextFontColor;
  .choose-btn {
    background: #F4F4F4;
    border: 1px solid #E5E5E5;
    border-radius: 2px;
    margin: 0 4px;
    padding: 0 2px;
    text-decoration: none;
  }
  .city-list {
    color: $supTextFontColor;
  }
}
</style>
