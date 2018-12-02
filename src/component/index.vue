<template>
  <div>
    <p>我是{{ user.name }}</p>
    <p>我来自{{ user.from }}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {}
    },
    props: {
      user: {
        type: Object
      }
    },
    methods: {

    }
  }
</script>

<style scoped lang='scss'>
</style>