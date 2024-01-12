<template>
  <div>
    <h2>这是一个标题</h2>
    <el-button type="primary" size="default" :icon="Plus">主要按钮</el-button>
  </div>
</template>
<script setup lang="ts">
import { Plus } from '@element-plus/icons-vue'
</script>
<style scoped lang="scss">
div {
  h2 {
    color: $color;
    font-weight: bold;
  }
}
</style>
