<template>
  <div>Products</div>
</template>

<script>
const VerticalProduct = require('../cards/VerticalProduct')

module.exports = {
  components: {
    VerticalProduct
  },
  data() {
    return {}
  },
  methods: {
    addToCart(index, quantity = 1) {
      this.$store.commit('addItemToCart', { itemId: index, quantity })
      this.$store.commit('updateSnackbar', { show: true })
    }
  }
}
</script>
