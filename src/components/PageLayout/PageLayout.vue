<template>
  <el-container>
    <el-scrollbar>
      <el-header>
        <header-layout />
      </el-header>
      <el-main>
        <slot></slot>
      </el-main>
    </el-scrollbar>
  </el-container>
</template>
<script lang="ts" setup>
import HeaderLayout from './components/HeaderLayout.vue'
</script>
<style lang="scss" scoped>
.el-header {
  height: auto;
  padding: 0;
  position: fixed;
  width: 100%;
}
.el-container {
  height: 100vh;
}
.el-scrollbar {
  width: 100vw;
}
.el-main {
  padding-top: var(--header-height);
}
</style>
