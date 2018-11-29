<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/my">我的美团</nuxt-link>
        <dl>
          <dd>
            <nuxt-link to="/order">我的订单</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/order">我的收藏</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/order">抵用券</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/order">账户设置</nuxt-link>
          </dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/my">手机app</nuxt-link>
      </li>
      <li class="list">
        <nuxt-link to="/my">商家中心</nuxt-link>
        <dl>
          <dd>
            <nuxt-link to="/userCenter">登录商家中心</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/coop">我想合作</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/wap">免费手机开店</nuxt-link>
          </dd>
          <dd>
            <nuxt-link to="/kaipiao">商家申请开票</nuxt-link>
          </dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/my">网站导航</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss">
  .m-nav {
    float: right;
    margin: 0;
    padding: 0;
    z-index: 999;

    .nav {
      list-style: none;
      float: right;
      height: 40px;
      > li {
        float: left;
        width: 78px;
        box-sizing: border-box;
        text-align: center;
        cursor: pointer;

        &.list:hover {
          border: 1px solid #E5E5E5;
          border-top: none;

          > dl {
            display: block;
          }
        }
        dl {
          background: #fff;
          display: none;
          z-index: 999;

          dd {
            line-height: 35px;

            &:hover {
              color: #31BBAC;
            }
          }
        }
      }
    }
  }

</style>
