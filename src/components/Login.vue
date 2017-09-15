<template>
  <div class="login">
    <h1>{{ msg }}</h1>
    <h2>YER CHECK THIS OUT {{ memes }}</h2>
  </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: 'DIS IS A NEW PAGE',
      memes: "<yee boi>"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
