<template>
  <div>
    <el-image
      style="width: 130px; height: 100px"
      :src="myurl"
      :preview-src-list="srcList"
    >
    </el-image>
    <el-table
      :data="data"
      style="width: 100%"
    >
      <el-table-column
        prop="clxh"
        label="车轮型号"
      >
      </el-table-column>
      <el-table-column
        prop="lkfby"
        label="螺孔分布圆"
      >
      </el-table-column>
      <el-table-column
        prop="zxk"
        label="中心孔"
      >
      </el-table-column>
      <el-table-column
        prop="lkccjsm"
        label="螺孔尺寸及数目"
      >
      </el-table-column>
      <el-table-column
        prop="lkxz"
        label="螺孔形状"
        width="180"
      >
      </el-table-column>
      <el-table-column
        prop="npj"
        label="内偏距（不含板厚）"
      >
      </el-table-column>
      <el-table-column
        prop="fbhd"
        label="辐板厚度"
      >
      </el-table-column>
      <el-table-column
        prop="sylt"
        label="适用轮胎"
        width="200"
      >
      </el-table-column>
    </el-table>
  </div>

</template>

  <script>
export default {
  props: {
    myurl: String,
    srcList: Array,
    data: Array
  },
  data() {
    return {
      
    };
  }
};
</script>