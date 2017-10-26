    <template>
      <div class="m-header">
        <div class="icon"></div>
        <h1 class="text">章鱼音乐</h1>
      </div>
    </template>

    <script>
        export default {}
    </script>
    <style scoped lang="stylus" rel="stylesheet/stylus">
      @import "~common/stylus/variable"
      @import "~common/stylus/mixin"

      .m-header
        height: 44px
        text-align: center
        color: $color-theme
        font-size: 0
        .icon
          height:30px
          width: 30px
          background-size:30px 30px
          vertical-align: top
          display: inline-block
          bg-image(zy)
          margin-top:6px
          margin-right: 9px
        .text
          display: inline-block
          font-size: $font-size-large
          vertical-align: top
          line-height: 44px
    </style>