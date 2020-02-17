<template>
  <div class="home">
    <el-row>
      <el-col :span="10">
        <el-card>

          <el-carousel trigger="click">
            <el-carousel-item>
              <img
                src="../assets/1.jpg"
                alt="1"
              >
            </el-carousel-item>
            <el-carousel-item>
              <img
                src="../assets/2.jpg"
                alt="2"
              >
            </el-carousel-item>
            <el-carousel-item>
              <img
                src="../assets/3.jpg"
                alt="3"
              >
            </el-carousel-item>
          </el-carousel>
        </el-card>

      </el-col>
      <el-col :span="14">
        <el-card class="card">
          <img
            src="../assets/xcx.jpg"
            alt=""
          >
          <img
            src="../assets/ewm.jpg"
            alt=""
          >
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>
<style  scoped>
.carousel_image_type {
  width: 100%;
}
.card {
  height: 50%;
}
</style>
