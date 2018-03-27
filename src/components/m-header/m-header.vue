<template>
  <div class="m-header">
      <div class="icon"></div>
      <div class="text">Chicken Music</div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="stylus" scoped>
    @import "../../common/stylus/variable"
    @import "../../common/stylus/mixin"

.m-header
    position relative
    height 44px
    text-align center
    color $color-theme
    font-size 0
    .icon
        display inline-block
        vertical-align top
</style>
