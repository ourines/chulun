<template>
  <el-tabs
    v-model="activeName"
    type="border-card"
  >
    <el-tab-pane
      label="6.5-16"
      name="first"
    >
      <MyTable
        :data=data
        :myurl="url"
        :srcList="srcList"
      >
      </MyTable>
    </el-tab-pane>

    <el-tab-pane
      label="5.50F-16"
      name="second"
    >
      <MyTable
        :data=data1
        :myurl="url1"
        :srcList="srcList1"
      >
      </MyTable>
    </el-tab-pane>
  </el-tabs>
</template>
<script>
import MyTable from "./16/table";
export default {
  data() {
    return {
      activeName: "second",
      url: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G10604111.jpg",
      srcList: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G10604111.jpg"
      ],
      url1:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G055063a.jpg",
      srcList1: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G055063a.jpg"
      ],
      data: [
        {
          clxh: "6.5-16",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          pj: "30",
          fbhd: "双辐8＋8",
          sylt: "8.25R16"
        },
        {
          clxh: "6.5-16",
          lkfby: "212",
          zxk: "161",
          lkccjsm: "8-φ24.5",
          lkxz: "直孔/ISO",
          pj: "125",
          fbhd: "12/10",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "205",
          zxk: "161",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "125",
          fbhd: "10",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "203.2",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "-35",
          fbhd: "双辐6＋6",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "15",
          fbhd: "双辐6＋6",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "35",
          fbhd: "双辐6＋6",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "81",
          fbhd: "12/10",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "222",
          zxk: "161",
          lkccjsm: "6-φ24.5",
          lkxz: "直孔/ISO",
          pj: "125",
          fbhd: "10",
          sylt: "8.25R16"
        },{
          clxh: "6.5-16",
          lkfby: "225",
          zxk: "176",
          lkccjsm: "10-φ27",
          lkxz: "SR18/DIN",
          pj: "135/125",
          fbhd: "10",
          sylt: "8.25R16"
        },
      ],
      data1: [
        {
          clxh: "5.50F-16",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          pj: "117/115",
          fbhd: "12/10/8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          pj: "106/98",
          fbhd: "12/10",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "115/100",
          fbhd: "12/10",
          sylt: "6.5-16"
        },{
         clxh: "5.50F-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "65/22",
          fbhd: "12/10",
          sylt: "6.5-16"
        },{
           clxh: "5.50F-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "5/0",
          fbhd: "10",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "203.2",
          zxk: "140",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          pj: "115/109",
          fbhd: "10/8",
          sylt: "6.5-16"
        },
        
        {
          clxh: "5.50F-16",
          lkfby: "203.2",
          zxk: "140",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          pj: "111/105",
          fbhd: "10",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "203.2",
          zxk: "133",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          pj: "111/105",
          fbhd: "10",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "203.2",
          zxk: "146",
          lkccjsm: "5-φ22.5",
          lkxz: "直孔/ISO",
          pj: "107",
          fbhd: "8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "203.2",
          zxk: "146",
          lkccjsm: "5-φ29",
          lkxz: "SR22/JAP",
          pj: "105",
          fbhd: "10",
          sylt: "6.5-16"
        },

        {
          clxh: "5.50F-16",
          lkfby: "205",
          zxk: "161",
          lkccjsm: "6-φ20.5",
          lkxz: "直孔/ISO",
          pj: "125/110",
          fbhd: "10/8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "180",
          zxk: "141",
          lkccjsm: "6-φ20.5",
          lkxz: "直孔/ISO",
          pj: "115",
          fbhd: "10/8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "180",
          zxk: "140",
          lkccjsm: "6-φ18.5",
          lkxz: "锥角80°/BSF80°",
          pj: "41",
          fbhd: "6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "180",
          zxk: "140",
          lkccjsm: "6-φ24",
          lkxz: "SR22/JAP",
          pj: "41",
          fbhd: "6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "180",
          zxk: "140",
          lkccjsm: "6-φ19",
          lkxz: "SR22/JAP",
          pj: "19",
          fbhd: "8",
          sylt: "6.5-16"
        },

        {
          clxh: "5.50F-16",
          lkfby: "180",
          zxk: "140",
          lkccjsm: "6-φ19",
          lkxz: "直孔/ISO",
          pj: "19",
          fbhd: "8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "184.15",
          zxk: "133",
          lkccjsm: "6-φ25.5",
          lkxz: "锥角90°/BSF90°",
          pj: "30",
          fbhd: "6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "184.15",
          zxk: "133",
          lkccjsm: "5-φ29",
          lkxz: "锥角90°/BSF90°",
          pj: "30",
          fbhd: "6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "140",
          zxk: "110.6",
          lkccjsm: "5-φ15",
          lkxz: "直孔/ISO",
          pj: "9/-8",
          fbhd: "8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "140",
          zxk: "110",
          lkccjsm: "5-φ15",
          lkxz: "直孔/ISO",
          pj: "0",
          fbhd: "8",
          sylt: "6.5-16"
        },
       
       {
          clxh: "5.50F-16",
          lkfby: "208",
          zxk: "150",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          pj: "111/105",
          fbhd: "10",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "170",
          zxk: "133",
          lkccjsm: "6-φ17.5",
          lkxz: "锥角60°/BSF60°",
          pj: "25",
          fbhd: "6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "160",
          zxk: "115",
          lkccjsm: "6-φ15",
          lkxz: "锥角60°/BSF60°",
          pj: "0",
          fbhd: "8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "139.7",
          zxk: "107",
          lkccjsm: "6-φ15",
          lkxz: "锥角60°/BSF60°",
          pj: "0",
          fbhd: "5",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "140",
          zxk: "94.5",
          lkccjsm: "5-φ18.5",
          lkxz: "SR18/DIN",
          pj: "26",
          fbhd: "8",
          sylt: "6.5-16"
        },

        {
          clxh: "5.50F-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "29",
          fbhd: "双辐8＋8",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          pj: "40",
          fbhd: "双辐6＋6",
          sylt: "6.5-16"
        },{
          clxh: "5.50F-16",
          lkfby: "140",
          zxk: "94.5",
          lkccjsm: "5-φ18.5",
          lkxz: "SR22/JAP",
          pj: "26",
          fbhd: "双辐8＋8",
          sylt: "6.5-16"
        },
      ],
    };
  },
  methods: {
    handleClick(tab, event) {
      console.log(tab, event);
    }
  },
  components: {
    MyTable
  }
};
</script>

<style>
</style>