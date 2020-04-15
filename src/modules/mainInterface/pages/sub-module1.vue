<template>
  <div>
    <h2>这是主界面模块下受前端路由控制的子模块</h2>
    <div>这一块的内容才是受前端路由控制的</div>
    <a href="http://localhost:8086/a">跳转到a模块内容页面</a>
    <a href="http://localhost:8086/b">跳转到b模块内容页面</a>
    <hello-world></hello-world>
  </div>
</template>

<script>
import HelloWorld from '../../../components/HelloWorld'
export default {
  name: 'c-sub-module1',
  components: {HelloWorld},
  data () {
    return {
    }
  },
  methods: {},
  created () {}
}
</script>
<style scoped>
</style>
