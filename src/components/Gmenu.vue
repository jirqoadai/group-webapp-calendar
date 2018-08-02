<template>
  <div class="g-menu">
    <el-row>
      <el-col :span="8"><div class="grid-content bg-purple">
        <el-button size="small" type="success" icon="el-icon-check" circle></el-button>
      </div></el-col>
      <el-col :span="8">
        <div class="grid-content bg-purple-light g-text-center">
          <el-button type="text">&lt;</el-button>
          <el-button type="text">2018-08-02</el-button>
          <el-button type="text">&gt;</el-button>
        </div>
      </el-col>
      <el-col :span="8"><div class="grid-content bg-purple g-minw">
        <el-button size="mini" type="primary">放假安排</el-button>
        <el-button size="mini" type="primary">农历节气</el-button>
        <el-button size="mini" type="primary">节日大全</el-button>
      </div></el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  data () {
    return {
      activeIndex: '1',
    }
  }
}
</script>

<style scoped>
  .g-text-center{
    text-align: center;
  }
  .g-menu{
    padding: 12px 8px;
  }
  .g-minw {
  }
</style>
