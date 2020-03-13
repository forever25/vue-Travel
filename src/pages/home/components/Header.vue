<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      {{searchValue}}
    </div>
    <div class="header-right">城市
      <span class="iconfont">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader',
  data () {
    return {
      searchValue: `输入城市\\景点\\游玩主题`
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl';
  .header
    display flex
    line-height .86rem
    background $bgColor
    color #fff
    .header-left
      width .64rem
      float left
      text-align center
    .header-input
      flex 1
      background-color #fff
      border-radius .1rem
      margin-top .12rem
      height .64rem
      line-height .64rem
      margin-left .2rem
      color #ccc
    .header-right
      float right
      width 1.24rem
      text-align center
</style>
