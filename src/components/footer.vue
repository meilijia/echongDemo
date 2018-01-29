<template>
  <div class="footer">footer</div>
</template>

<script>
export default {
  name: 'index-footer'
}
</script>

<style lang="stylus" scoped>
  @import '../assets/styles/common/varibles.styl'
  .footer
    position: fixed
    bottom: 0
    height: 1.1rem
    width: 100%
    color: #fff
    border-top: 1px solid $lightFontColor
</style>
