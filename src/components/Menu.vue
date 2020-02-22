<template>
  <el-row>
    <el-col
      class="title"
      :xs="12" :md="4"
    >
      <h3 class="title">昆明楚轮商贸有限公司</h3>
    </el-col>
    <el-col :xs="12" :md="20">
      <el-menu
        :default-active="activeIndex2"
        class="el-menu-demo"
        mode="horizontal"
        @select="handleSelect"
        background-color="#545c64"
        text-color="#f6f6e9"
        active-text-color="#ffd04b"
        router
      >
        <el-menu-item index="/">产品中心</el-menu-item>
      </el-menu>
    </el-col>
  </el-row>

</template>

<script>
export default {
  data() {
    return {
      activeIndex: "1",
      activeIndex2: "1"
    };
  },
  methods: {
  }
};
</script>
<style scoped>
.title {
  height: 60px;
  font-size: 20px;

  background-color: #545c64;
  text-align: center;
  line-height: 60px;
  color: azure;
}

</style>