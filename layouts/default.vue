<template>
  <el-container class="layout-default">
    <el-header height="211px">
      <my-header />
    </el-header>
    <el-main>
      <nuxt />
    </el-main>
    <el-footer height="100%">
      <my-footer></my-footer>
    </el-footer>
  </el-container>
</template>

<script>
import MyHeader from '@/components/public/header/index'
import MyFooter from '@/components/public/footer/index.vue'
export default {
  components: {
    MyHeader,
    MyFooter
  }
}
</script>
