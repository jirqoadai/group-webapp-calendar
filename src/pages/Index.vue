<template>
  <div>
    <el-container class="g-page">
      <el-header>
        <Gheader></Gheader>
      </el-header>
      <el-container>
        <el-aside><Gaside></Gaside></el-aside>
        <el-container>
          <el-header><Gmenu></Gmenu></el-header>
          <el-main><Gmain></Gmain></el-main>
        </el-container>
      </el-container>
      <el-footer>
        <Gfooter></Gfooter>
      </el-footer>
    </el-container>
  </div>
</template>

<script>
import Gheader from '../components/Gheader'
import Gfooter from '../components/Gfooter'
import Gaside from '../components/Gaside'
import Gmenu from '../components/Gmenu'
import Gmain from '../components/Gmain'

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
  },
  components: {
    Gheader,
    Gfooter,
    Gaside,
    Gmenu,
    Gmain
  }
}
</script>

<style lang="scss">
  .g-page{
    position: relative;
    height: 100vh;
  }
  .el-aside {
    border-right: 1px solid #eaeaea;
    box-sizing: border-box;
  }
</style>
