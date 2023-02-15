<script setup lang="ts">
import LayoutSidebar from '@/components/layout/LayoutAside.vue'
import LayoutMain from '@/components/layout/LayoutMain.vue'
import LayoutHeader from '@/components/layout/LayoutHeader.vue'
</script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header>
        <LayoutHeader></LayoutHeader>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <LayoutSidebar></LayoutSidebar>
        </el-aside>
        <el-main>
          <LayoutMain></LayoutMain>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<style>
.common-layout {
  display: flex;
  height: 100vh;
}
</style>
