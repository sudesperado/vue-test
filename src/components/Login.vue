<template>
  <div id = 'login'>
      <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      msg: '欢迎登录'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
}
</style>