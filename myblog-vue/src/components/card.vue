<template>
    <el-card :shadow="false"style="width: 607px;height: 269px; border-width: 0;border-radius: 0; /* 设置边框宽度为0，也可以去掉边框 */">
    <template #header>
      <div class="card-header">
        <span>文章标题</span>
      </div>
    </template>
    <p class="show">向后端请求数据展示内容</p>
    <template #footer>标签和阅读量</template>
    </el-card>
</template>

<script setup lang="ts">



</script>
<style scoped>
.show{
  -webkit-line-clamp: 3;
  line-height: 24px;
  -webkit-box-orient: vertical;
}
</style>