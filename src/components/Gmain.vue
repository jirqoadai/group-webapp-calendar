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
      cards: ['1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1', '1']
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
  .g-cards{
    height: 100%;
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: flex-end;
  }
  .g-card {
    height: calc((100vh - 120 -20) / 5);
    flex: 0 0 14.285714285%;
    text-align: center;
  }
</style>
