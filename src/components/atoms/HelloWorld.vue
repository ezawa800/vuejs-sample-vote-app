<template lang="pug">
  div.hello
    h1 {{ msg }}
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to My Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
primary-color = #42b983

h1
  color: darken(primary-color, 10%);

</style>
