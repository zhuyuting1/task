<template>
  <div class="header">
    <div class="header-warpper">
      <i class="menu icon-menu"></i>
      <i class="find icon-wangyi"></i>
      <i class="community icon-community"></i>
      <i class="search icon-search"></i>
    </div>
  </div>
</template>
<style lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/global.styl"
  .header
    position:fixed
    top:0
    left:0
    right:0
    height:50px
    z-index:10
    background:$primarycolor
    .header-warpper
      height:100%
      background:$primarycolor
      display:flex
      align-items:center
      justify-content:space-between
      .icon-menu,.icon-search
        color:#fff
        font-size:26px
        padding:10px 15px
      .centermenu
        font-size:24px
        i
          margin:0 5px
          color:#eee
          &.router-link-active
            i
              color:#CCAFAF
          &.active
            color:#4AE0A8

          &.music
            font-size:22px
      .counter
        position:absolute
        background:green
        width:600px
        height:150px
        color:#fff
        font-size:20px
        top:0
        left:120px
        p
          height:30px
          line-height:30px
</style>
