<template>
  <div class="g-footer">
    <el-row :gutter="20">
      <el-col :span="6"><div class="grid-content bg-purple">已关注22万</div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple">联系我们 | 关于我们</div></el-col>
      <el-col :span="12"><div class="grid-content bg-purple g-text-right g-text-small">公安局备案号：457240754728057<br/>&copy;2010-2018 Youloft.,ICP:1100003103</div></el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  }
}
</script>

<style>
  .g-footer{
    padding-top: 12px;
    border-top: 1px solid #eaeaea;
    box-sizing: border-box;
    height: 60px;
  }
  .g-text-small{
    font-size: 12px;
  }
  .g-text-right{
    text-align: right;
  }
</style>
