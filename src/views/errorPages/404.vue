<template>
    <p>你查找的页面不存在,<router-link :to="{ name: 'home' }">点击返回首页</router-link></p>
</template>

<script>
  // 组件的所有代码都在这里
  export default {
    name: '404',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    },
    methods: {
      //组件内的方法
    },
    computed: {
      //计算属性
    },
    mounted() {
      //元素装载完后执行的动作
      //this.(function () {
      // 代码保证 this. 在 document 中 已被渲染

      //})
    }
  }
</script>

<style scoped>
    /* CSS 在这里
   * 通过包含 `scoped`, 我们确保所有的 CSS
   * 仅作用于这个组件！
   */
</style>
