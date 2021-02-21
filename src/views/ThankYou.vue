<template>
  <div>
    Thank you
  </div>
</template>

<script>
module.exports = {
  data() {
    return {
      overlay: false
    }
  },
  mounted() {
    setTimeout(() => {
      this.overlay = false
    }, 3000)
  },
  beforeMount() {
    this.overlay = true
  }
}
</script>
