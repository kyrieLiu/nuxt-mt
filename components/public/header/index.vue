<!--
   User: Liu Yin
   Date: 2020/1/28
   Description:
 -->
<template>
  <el-row :gutter="15" class="m-header">
    <el-col :span="6">
      <geo />
    </el-col>
    <el-col :span="6">
      <user/>
    </el-col>
    <el-col :span="6" />
  </el-row>
</template>

<script>
import geo from './geo'
import user from './user'
export default {
  components: {
    geo,
    user
  },
  data () {
    return {}
  },
  methods: {}
}
</script>

<style lang="scss" scoped>
  @import "@/assets/css/public/layout.scss";
</style>
