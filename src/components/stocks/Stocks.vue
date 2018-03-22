<template>
    <div>
      <h1>The Stocks Component</h1>
      <app-stock></app-stock>
    </div>
</template>

<script>
import Stock from './Stock.vue'
  export default {
    components: {
      appStock: Stock
    }
  }
</script>