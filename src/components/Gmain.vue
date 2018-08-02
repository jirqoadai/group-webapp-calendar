<template>
  <div class="g-cards">
    <div v-for="card in cards" class="g-card" v-bind:key="card.index">
      <div>
        bababa
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      cards: ['1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1']
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style lang="scss">
  .g-cards{
    height: 100%;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: flex-end;
  }
  .el-main {
    padding: 0;
  }
  .g-card {
    border: 1px solid #eaeaea;
    border-left: 0px;
    border-bottom: 0px;
    box-sizing: border-box;
    min-height: calc((100vh - 240px) / 5);
    flex: 0 0 14.285714285%;
    text-align: center;
    &:nth-of-type(7n) {

    }
  }
</style>
