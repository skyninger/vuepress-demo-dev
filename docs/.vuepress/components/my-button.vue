<template>
  <button @click="clickButton">测试一个按钮</button>
</template>

<script>
  export default {
    data () {
      return {}
    },
    methods: {
      clickButton () {
        window.alert('测试成功')
      }
    }
  }
</script>