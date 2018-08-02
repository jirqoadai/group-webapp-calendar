<template>
  <div class="g-menu">
    <el-row>
      <el-col :span="8"><div class="grid-content bg-purple">
        <el-button size="small" type="success" icon="el-icon-check" circle></el-button>
      </div></el-col>
      <el-col :span="8">
        <div class="grid-content bg-purple-light">
          <el-button type="text">&lt;</el-button>
          <el-button type="text">2018-08-02</el-button>
          <el-button type="text">&gt;</el-button>
        </div>
      </el-col>
      <el-col :span="8"><div class="grid-content bg-purple g-minw">
        <el-button type="primary">放假安排</el-button>
        <el-button type="primary">农历节气</el-button>
        <el-button type="primary">节日大全</el-button>
      </div></el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  data () {
    return {
      activeIndex: '1',
      activeIndex2: '1'
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style>
  .g-menu{
    padding: 12px 8px;
  }
  .g-minw {
    min-width: 360px;
  }
</style>
