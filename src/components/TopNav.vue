<template>
  <v-app-bar>
    <v-toolbar-title>TopNav</v-toolbar-title>
  </v-app-bar>
</template>

<script>
module.exports = {
  data() {
    return {
      drawer: false,
      items: [
        { title: 'Home', link: '/', icon: 'home' },
        { title: 'Store', link: 'store', icon: 'shopping-basket' },
        { title: 'Cart', link: 'cart', icon: 'shopping-cart' }
      ]
    }
  }
}
</script>
