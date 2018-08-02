<template>
  <div class="g-footer">
    <el-row :gutter="20">
      <el-col :span="6"><div class="grid-content bg-purple g-text-small">
        <el-button size="medium">已关注22万</el-button>
        <el-button size="medium">加入qq群</el-button>
      </div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple g-text-small">
        <el-button type="text" size="medium">联系我们</el-button><el-button type="text">|</el-button><el-button type="text" size="medium">关于我们</el-button>
      </div></el-col>
      <el-col :span="12"><div class="grid-content bg-purple g-text-right g-text-mini">公安局备案号：457240754728057<br/>&copy;2010-2018 Youloft.,ICP:1100003103</div></el-col>
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
    font-size: 14px;
  }
  .g-text-mini{
    font-size: 12px;
  }
  .g-text-right{
    text-align: right;
  }
</style>
