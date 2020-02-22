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
        prop="ggxh"
        label="规格型号"
      >
      </el-table-column>
      <el-table-column
        prop="sc"
        label="俗称"

      >
      </el-table-column>
      <el-table-column
        prop="cz"
        label="材质"
      >
      </el-table-column>
      <el-table-column
        prop="wpj"
        label="外偏距"
      >
      </el-table-column>
      <el-table-column
        prop="lskgsjzj"
        label="螺栓孔个数及直径"
        width="180"
      >
      </el-table-column>
      <el-table-column
        prop="lmz"
        label="螺母座"
      >
      </el-table-column>
       <el-table-column
        prop="fby"
        label="分布圆"
      >
      </el-table-column>
      <el-table-column
        prop="zk"
        label="中孔"
      >
      </el-table-column>
      <el-table-column
        prop="lfhd"
        label="轮辐厚度"
      >
      </el-table-column>
      <el-table-column
        prop="qmzxh"
        label="气门嘴型号"
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