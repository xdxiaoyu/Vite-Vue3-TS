<template>
  <!-- <img class="img" alt="Vue logo" src="https://vitejs.cn/logo.svg" /> -->
  <HelloWorld msg="Hello Vue 3 + Vite + TypeScript" />
  <!-- <echartsList></echartsList> -->
</template>

<script setup lang="ts">
import * as echarts from 'echarts'
import { provide } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'
import echartsList from '@/components/Demo/echarts.vue'

provide('ec', echarts)
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.img {
  width: 100px;
}
</style>
