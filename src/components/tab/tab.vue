<template>
  <div class="tab">
    <router-link tag="div" class="tab-item" to="/recommend">
      <span class="tab-text">推荐</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/singer">
      <span class="tab-text">歌手</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/rank">
      <span class="tab-text">排行</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/search">
      <span class="tab-text">搜索</span>
    </router-link>
  </div>
</template>
<script>
  export default {}
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable.styl"
  .tab
    height:44px
    line-height:44px
    display:flex
    font-size: $font-size-medium
    .tab-item
      flex:1
      text-align: center
      .tab-text
        color: $color-text-l
        padding-bottom: 5px
      &.router-link-active
        .tab-text
          color: $color-theme
          border-bottom: 2px solid $color-theme
</style>