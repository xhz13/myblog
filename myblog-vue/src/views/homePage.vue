<script setup lang="ts">
import card from "../components/card.vue";
import navigation from "../components/navigation.vue";
import readCrumb from "../components/readCrumb.vue";
</script>

<template>
  <div class="background">
    <div class="navigation">
      <navigation/>
    </div>
    <div class="content">
      <div class="contentmain">
        <readCrumb/>
      <div class="card">
        <card/>
        <card/>
        <card/>
      </div>
    </div>
      <div class="sidebar">
      </div>
    </div>
  </div>
</template>

<style>
.background {
  /* 内容竖向排列 */
  display: flex;
  flex-direction: column;
}
.content {
  /* 内容横向排列 */
  display: flex;
  justify-content: space-evenly;
}
.card {
  /* margin-right: 30px; */
  display: flex;
  padding-top: 50px;
  flex-direction: column; /* 横向排列内容 */
  justify-content: space-between; /* 内部内容在水平方向上均匀分布 */
  /* width: 400px; 每个 card 占据一半的宽度 */
}
.sidebar {
  /* margin-left: 30px; */
  width: 300px;
  height: 1000px;
  background-color: #f0f0f0;
}

</style>
