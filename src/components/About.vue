<template>
  <div>
    <h1>This is a about page</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'Welcome to our site. I myself is Piko. Piko Monde.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
