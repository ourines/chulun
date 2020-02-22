<template>
  <div id="app">
    <el-container>
      <el-header>
        <Menu></Menu>
      </el-header>
      <el-main>
    <router-view></router-view>

      </el-main>
    </el-container>
  </div>
</template>

<script>

import Menu from './components/Menu'
export default {
  name: 'app',
  components: {
    Menu
  }
}
</script>

<style scoped>
.el-header{
 padding: 0px; 
}
</style>
