<template>
  <router-view />
</template>

<style lang="scss">
html,
body {
  margin: 0;
  padding: 0;
}

// 链接样式
.contributor-link {
  color: #2196f3; // 默认使用适中的蓝色
  text-decoration: none;
  transition: all 0.3s ease; // 添加过渡效果

  &:visited {
    color: #2196f3;
  }

  &:hover {
    color: #1976d2; // 悬停时使用深蓝色
  }

  &:active {
    color: #0d47a1 !important; // 点击时使用更深的蓝色
  }
}
</style>
