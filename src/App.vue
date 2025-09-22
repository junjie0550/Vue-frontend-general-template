<template>
  <div id="app">
    <BasicLayout/>
  </div>
</template>

<script setup lang="ts">

import BasicLayout from '@/layout/BasicLayout.vue'
/*import { healthUsingGet } from '@/api/mainController.ts'
import { useLoginUserStore } from '@/stores/useLoginUserStore.ts'

// 改为在权限校验文件中获取
// 获取当前登录用户信息
const loginUserStore = useLoginUserStore()
loginUserStore.fetchLoginUser()

// 测试前后端接口是否正常通信
healthUsingGet().then((res) => {
  console.log(res)
})*/
</script>

<style scoped>

</style>
