<script>
// 测试2
export default {
  data () {
    return {
      userInfo: {}
    }
  },
  async onLaunch () {
    console.log('onLaunch')
  },
  onHide () {
    console.log('App Hide')
  },
  onUnload () {
    console.log('onUnload')
  }
}
</script>

<style lang="scss">
/* 注意要写在第一行，同时给style标签加入lang="scss"属性 */
@import "uview-ui/index";
body{
  //@include bis('./static/image/backgroundWhite.png')
  //background: linear-gradient(50%, #999, #444);
   background: linear-gradient(180deg, #999 0%, #555 100%);
}
page{
  background-color: $uni-color-bg;
  min-height:100vh;
}
</style>
