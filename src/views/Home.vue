<template>
  <div class="home">
    <el-row :gutter="10">
      <el-col :span="12">
        <el-card>
          <el-carousel
            trigger="click"
            height="400px"
          >
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

      <el-col :span="12">
        <el-card class="card">
          <el-row>
            <h3>更多信息请使用微信扫描下方二维码</h3>
          </el-row>
          <el-row class="img-row">
            <img
              src="../assets/xcx.jpg"
              alt=""
            >
            <img
              src="../assets/ewm.jpg"
              alt=""
            >
          </el-row>
          <el-divider></el-divider>
          <el-row>
            <span>订购电话 :</span>
            <h4>施承荣 137-0065-3042</h4>
          </el-row>
        </el-card>
      </el-col>
    </el-row>
    <el-row class="my-row">
      <el-collapse
        v-model="activeNames"
        @change="handleChange"
      >
        <el-collapse-item
          title="铝合金车轮"
          name="1"
        >
          <LHJCL></LHJCL>
        </el-collapse-item>
        <el-collapse-item
          title="护胎霸型钢车轮"
          name="2"
        >
          <HTBXGCL></HTBXGCL>
        </el-collapse-item>
        <el-collapse-item
          title="无内胎车轮"
          name="3"
        >
          <WNTCL></WNTCL>
        </el-collapse-item>
        <el-collapse-item
          title="-16车轮"
          name="4"
        >
          <SL></SL>
        </el-collapse-item>
      </el-collapse>

    </el-row>
  </div>
</template>

<script>
// @ is an alias to /src
import LHJCL from '../components/lhjcl'
import HTBXGCL from '../components/htbxgcl'
import WNTCL from '../components/wntcl'
import SL from '../components/16'

export default {
  name: "Home",
  data() {
    return {
      activeNames: ["1"]
    };
  },
  methods: {
  },
  components:{
    LHJCL,
    HTBXGCL,
    WNTCL,
    SL
  }
};
</script>
<style  scoped>
.carousel_image_type {
  width: 100%;
}
.card {
  height: 50%;
}
h3 {
  text-align: center;
  padding-bottom: 18px;
}

.img-row {
  text-align: center;
}
.my-row{
  margin-top: 10px;
}
</style>
