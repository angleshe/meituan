<template>
  <ul class="nav">
    <li class="item">
      <nuxt-link class="nav-title" to="./myMeiTuan">我的美团</nuxt-link>
      <ul class="nav-list">
        <li class="list-item"><nuxt-link class="item" to="./myOrder">我的订单</nuxt-link></li>
        <li class="list-item"><nuxt-link class="item" to="./myCollection">我的收藏</nuxt-link></li>
        <li class="list-item"><nuxt-link class="item" to="./myCoupon">抵用劵</nuxt-link></li>
        <li class="list-item"><nuxt-link class="item" to="./myOrder">账号设置</nuxt-link></li>
      </ul>
    </li>
    <li class="item">
      <nuxt-link class="nav-title" to="./app">手机APP</nuxt-link>
    </li>
    <li class="item">
      <nuxt-link class="nav-title" to="">商家中心</nuxt-link>
      <!-- <ul class="nav-list">
        <li><nuxt-link class="item" to="./businessCenter">登录商家中心</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">美团智能收银</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">我想合作</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">手机免费开店</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">餐饮代理招募</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">商家申请开票</nuxt-link></li>
        <li><nuxt-link class="item" to="./businessCenter">免费合作美团排队</nuxt-link></li>
      </ul> -->
    </li>
    <li class="item">
      <nuxt-link class="nav-title" to="./network">网站导航</nuxt-link>
      <!-- <div class="nav-container">
        <dl class="group">
          <dt class="group-title">酒店旅游</dt>
          <dd class="group-container">
            <ul>
              <li class="group-item"><nuxt-link class="item-link">国际机票</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">经济型酒店</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">公寓</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">青年旅社</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">农家院</nuxt-link></li>
            </ul>
            <ul>
              <li class="group-item"><nuxt-link class="item-link">火车票</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">主题酒店</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">豪华酒店</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">度假酒店</nuxt-link></li>
            </ul>
            <ul>
              <li class="group-item"><nuxt-link class="item-link">榛果民宿</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">商务酒店</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">客栈</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">别墅</nuxt-link></li>
            </ul>
          </dd>
        </dl>
        <dl class="group">
          <dt class="group-title">吃美食</dt>
          <dd class="group-container">
            <ul>
              <li class="group-item"><nuxt-link class="item-link">烤鱼</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">烧烤</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">火锅</nuxt-link></li>
            </ul>
            <ul>
              <li class="group-item"><nuxt-link class="item-link">特色小吃</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">自助餐</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">代金劵</nuxt-link></li>
            </ul>
          </dd>
        </dl>
        <dl class="group">
          <dt class="group-title">手机应用</dt>
          <dd class="group-container">
            <ul>
              <li class="group-item"><nuxt-link class="item-link">国际机票</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">经济型酒店</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">公寓</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">青年旅社</nuxt-link></li>
              <li class="group-item"><nuxt-link class="item-link">农家院</nuxt-link></li>
            </ul>
          </dd>
        </dl>
      </div> -->
    </li>
  </ul>
</template>

<style lang="scss" scoped>
.nav {
  display: flex;
  font-size: $supTextFontSize;
  .item {
    flex: 1;
    height: 40px;
    &:hover {
      background-color: #fff;
      border-color: #E5E5E5;
      box-shadow: 0 3px 5px 0 rgba(0,0,0,.1);
    }
    .nav-title {
      @include textCenter(40);
      display: block;
      color: $subtextFontColor;
      &:hover {
        color: $mainColor;
      }
    }
    .nav-list {
      background-color: #fff;
      border-color: #E5E5E5;
      box-shadow: 0 3px 5px 0 rgba(0,0,0,.1);
      .list-item {
        display: flex;
        align-items: stretch;
        .item {
          flex: 1;
          display: block;
          @include textCenter(40);
        }
      }
    }
    // .nav-list,
    // .nav-container{
    //   display: none;
    // }
  }
}
</style>
