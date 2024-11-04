<template>
  <div class="nav-wrapper">
    <div class="logo">
      <el-image
        style="width: 48px; height: 48px; padding-top: 4px"
        src="/gennisa tech logo.svg"
        fit="fit"
      />
      <span>格尼撒小队 | Gennisa Team</span>
    </div>
  </div>
</template>
<script lang="ts" setup></script>
<style lang="scss" scoped>
.nav-wrapper {
  height: var(--header-height);
  border-bottom: 1px solid #dcdfe6;
  display: flex;
  align-items: center;
  padding: {
    left: 32px;
    right: 32px;
  }
  position: relative;
  background-image: radial-gradient(transparent 1px, #ffffff 1px);
  background-size: 4px 4px;
  backdrop-filter: saturate(50%) blur(4px);
  @media screen and (max-width: 720px) {
    padding: {
      left: 8px;
      right: 8px;
    }
  }
}
.logo {
  display: flex;
  align-items: center;
  span {
    padding-left: 8px;
    font-size: 20px;
    font-weight: bold;
    @media screen and (max-width: 720px) {
      font-size: 16px;
    }
  }
}
</style>
