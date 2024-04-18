<template>
    <div>
        <el-avatar :size="size" :src="circleUrl" />
    </div>
</template>

<script setup lang="ts">
    import { ref } from 'vue'
    const size = ref('large')
    const circleUrl = ref('https://cube.elemecdn.com/6/94/4d3ea6c136348af54034b84b8c81apng.png')
</script>

<style scoped>

</style>