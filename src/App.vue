<!--
SPDX-FileCopyrightText: 2023 UnionTech Software Technology Co., Ltd.

SPDX-License-Identifier: LGPL-3.0-or-later
-->

<template>
  <Main />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Main from './components/Main.vue';

export default defineComponent({
  name: 'App',
  components: {
    Main,
  },
});
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

::-webkit-scrollbar {
    width: 0; /* 对于垂直滚动条，将其宽度设置为0 */
    /* height: 0; 如果你需要隐藏水平滚动条，取消注释并设置高度为0 */
}

/* 隐藏滚动条轨道 */
::-webkit-scrollbar-track {
    background: transparent; /* 轨道背景透明 */
}

/* 隐藏滚动条滑块 */
::-webkit-scrollbar-thumb {
    background: transparent; /* 滑块也透明 */
    border: none; /* 移除滑块边框 */
}
</style>
