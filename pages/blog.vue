<template>
  <div class="container">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Blog'
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        //
        { hid: 'description', name: 'description', content: 'Blog' }
      ]
    }
  }
}
</script>
