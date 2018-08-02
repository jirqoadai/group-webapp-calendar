<template>
  <div class="g-cards">
    <div v-for="card in cards" class="g-card-menu" v-bind:key="card.index">
      <div>
        {{card}}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      activeIndex: '1',
      cards: ['日', '一', '二', '三', '四', '五', '六']
    }
  },
  methods: {
    handleSelect (key, keyPath) {
      console.log(key, keyPath)
    }
  }
}
</script>

<style scoped>
  .g-menu{
    padding: 12px 8px;
  }
  .g-minw {
    min-width: 360px;
  }
  .g-cards{
    /* border-bottom: 1px solid #eaeaea; */
  }
  .g-card-menu {
    flex: 0 0 14.285714285%;
    text-align: center;
  }
</style>
