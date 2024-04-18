<template>
  <el-breadcrumb separator="      ">
    <el-breadcrumb-item :to="{ path: '/' }">homepage</el-breadcrumb-item>
    <el-breadcrumb-item><a href="/">promotion management</a></el-breadcrumb-item>
    <el-breadcrumb-item>promotion list</el-breadcrumb-item>
    <el-breadcrumb-item>promotion detail</el-breadcrumb-item>
  </el-breadcrumb>
</template>


<script setup lang="ts">

</script>

<style scoped>
.el-breadcrumb__item {
  margin-right: 20px; /* 右边距 */
  margin-left: 20px;  /* 左边距 */
}
.el-breadcrumb {
  margin-top: 40px; /* 上边距 */
  border-bottom: 1px solid #d8d6d6; /* 下边框 */
  padding: 15px;
}

</style>