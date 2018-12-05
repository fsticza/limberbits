<template>
  <div class="container mt-3">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'About'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        //
        { hid: 'description', name: 'description', content: 'About' }
      ]
    }
  }
}
</script>
