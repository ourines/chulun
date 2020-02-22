<template>
  <el-tabs
    v-model="activeName"
    type="border-card"
  >
    <el-tab-pane
      label="26DW×20"
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
      label="24.5-22.5×8.25"
      name="second"
    >
      <MyTable
        :data=data1
        :myurl="url1"
        :srcList="srcList1"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="22.5×11.75"
      name="third"
    >
      <MyTable
        :data=data2
        :myurl="url2"
        :srcList="srcList2"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="22.5×8.25-9.001"
      name="fourth"
    >
      <MyTable
        :data=data3
        :myurl="url3"
        :srcList="srcList3"
      >
      </MyTable>
    </el-tab-pane>
    <!-- this -->
    <el-tab-pane
      label="22.5×7.50"
      name="4"
    >
      <MyTable
        :data=data4
        :myurl="url4"
        :srcList="srcList4"
      >
      </MyTable>
    </el-tab-pane>

    <el-tab-pane
      label="19.5×6.75~7.50"
      name="5"
    >
      <MyTable
        :data=data5
        :myurl="url5"
        :srcList="srcList5"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="16×5.5OK"
      name="6"
    >
      <MyTable
        :data=data6
        :myurl="url6"
        :srcList="srcList6"
      >
      </MyTable>
    </el-tab-pane>

  <el-tab-pane
      label="17.5×6.00"
      name="7"
    >
      <MyTable
        :data=data7
        :myurl="url7"
        :srcList="srcList7"
      >
      </MyTable>
    </el-tab-pane>
  </el-tabs>
</template>
<script>
import MyTable from "./wntcl/table";
export default {
  data() {
    return {
      activeName: "second",
      url: "http://www.zenixauto.com/uploads/allimg/141027/1-14102H006031X.jpg",
      srcList: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102H006031X.jpg"
      ],
      url1:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95931130.jpg",
      srcList1: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95931130.jpg"
      ],
      url2: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95F0B4.jpg",
      srcList2: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95F0B4.jpg"
      ],
      url3:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95244435.jpg",
      srcList3: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G95244435.jpg"
      ],
      url4: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G94Q5A1.jpg",
      srcList4: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G94Q5A1.jpg"
      ],
      url5: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G94511550.jpg",
      srcList5: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G94511550.jpg"
      ],
      url6: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G93K6142.jpg",
      srcList6: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G93K6142.jpg"
      ],
      url7: "http://www.zenixauto.com/uploads/allimg/141027/1-14102G92U6352.jpg",
      srcList7: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G92U6352.jpg"
      ],
      data: [
        {
          clxh: "26×DW20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ27",
          lkxz: "SR18/DIN",
          npj: "50",
          fbhd: "12",
          qmzxh: "TRCH3",
          sylt: "23.1-26"
        },
        {
          clxh: "26×DW20",
          lkfby: "425",
          zxk: "370",
          lkccjsm: "10-φ24",
          lkxz: "SR18/DIN",
          npj: "67.5",
          fbhd: "18",
          qmzxh: "TRCH3",
          sylt: "23.1-26"
        }
      ],
      data1: [
        {
          clxh: "24.5X8.25",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "155//151",
          fbhd: "16/14",
          qmzxh: "V3-20-6",
          sylt: "11R24.5"
        }
      ],
      data2: [
        {
          clxh: "22.5X11.75",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "50/0/-12",
          fbhd: "16/14/12",
          qmzxh: "TR570C",
          sylt: "365/70R22.5, 385/65R22.5"
        },
        {
          clxh: "22.5X11.75",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "45",
          fbhd: "16/14/12",
          qmzxh: "TR570C",
          sylt: "365/70R22.5, 385/65R22.5"
        }
      ],
      data3: [
        {
          clxh: "22.5X9.00",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ISO",
          npj: "161",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X9.00",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ27",
          lkxz: "SR18/DIN",
          npj: "161/164",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X9.00",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ISO",
          npj: "161",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X9.00",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "161",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X9.00",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "161/151",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X9.00",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "161",
          fbhd: "16/14/12",
          qmzxh: "V3-20-6",
          sylt: "12R22.5, 295/80R22.5, 315/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "155/151",
          fbhd: "16/14/12",
          qmzxh: "V3-20-4",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "155/151",
          fbhd: "16/14/12",
          qmzxh: "V3-20-4",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "155/151",
          fbhd: "16/14/12",
          qmzxh: "V3-20-4",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "157/153",
          fbhd: "12",
          qmzxh: "TR572(外置）",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "155/151",
          fbhd: "16/14/12",
          qmzxh: "V3-20-4",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        },
        {
          clxh: "22.5X8.25",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "155/151/142",
          fbhd: "16/14/12",
          qmzxh: "V3-20-4",
          sylt: "11R22.5, 285/60R22.5, 295/80R22.5"
        }
      ],
      data4: [
        {
          clxh: "22.5X7.50",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "151/148/144",
          fbhd: "14/12",
          qmzxh: "V3-20-4",
          sylt: "10R22.5, 275/70R22.5"
        },
        {
          clxh: "22.5X7.50",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "155/151",
          fbhd: "14/12",
          qmzxh: "V3-20-4",
          sylt: "10R22.5, 275/70R22.5"
        },{
          clxh: "22.5X7.50",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "151",
          fbhd: "14/12",
          qmzxh: "V3-20-4",
          sylt: "10R22.5, 275/70R22.5"
        },{
          clxh: "22.5X7.50",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "151",
          fbhd: "14/12",
          qmzxh: "V3-20-4",
          sylt: "10R22.5, 275/70R22.5"
        },{
          clxh: "22.5X7.50",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "155/151",
          fbhd: "14/12",
          qmzxh: "V3-20-4",
          sylt: "10R22.5, 275/70R22.5"
        }
      ],
      data5: [
        {
          clxh: "19.5X7.50",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          npj: "137/133/127",
          fbhd: "12",
          qmzxh: "V3-20-4",
          sylt: "265/70R19.5, 245/70R19.5"
        },
       {
          clxh: "19.5X7.50",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "139",
          fbhd: "12",
          qmzxh: "V3-20-4",
          sylt: "265/70R19.5, 245/70R19.5"
        },{
          clxh: "19.5X7.50",
          lkfby: "245",
          zxk: "204",
          lkccjsm: "6-φ21",
          lkxz: "直孔/ISO",
          npj: "129",
          fbhd: "12",
          qmzxh: "V3-20-4",
          sylt: "265/70R19.5, 245/70R19.5"
        },

        {
          clxh: "19.5X6.75",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          npj: "135/115/108",
          fbhd: "12",
          qmzxh: "PVR-51B",
          sylt: "225/70R19.5"
        },{
          clxh: "19.5X7.50",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "135",
          fbhd: "12",
          qmzxh: "PVR-51B",
          sylt: "225/70R19.5"
        },{
          clxh: "19.5X7.50",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "135",
          fbhd: "12",
          qmzxh: "PVR-51B",
          sylt: "225/70R19.5"
        },
      ],
      data6: [
        {
          clxh: "16X5.50K",
          lkfby: "203.2",
          zxk: "146",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          npj: "107",
          fbhd: "8",
          qmzxh: "PVR181",
          sylt: "6.50R16"
        },
        {
          clxh: "16X5.50K",
          lkfby: "203.2",
          zxk: "146",
          lkccjsm: "5-φ29",
          lkxz: "SR22/JAP",
          npj: "107",
          fbhd: "8",
          qmzxh: "PVR181",
          sylt: "6.50R16"
        },{
          clxh: "16X5.50K",
          lkfby: "208",
          zxk: "146",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          npj: "107",
          fbhd: "8",
          qmzxh: "PVR181",
          sylt: "6.50R16"
        },{
          clxh: "16X5.50K",
          lkfby: "190",
          zxk: "140",
          lkccjsm: "6-φ20.5",
          lkxz: "SR22/JAP",
          npj: "115",
          fbhd: "10",
          qmzxh: "PVR181",
          sylt: "6.50R16"
        },
      ],
      data7:[
        { 
          clxh: "17.5×6.00",
          lkfby: "222.25",
          zxk: "163",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          npj: "125/123/117",
          fbhd: "12/10",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        },
         { 
          clxh: "17.5×6.00",
          lkfby: "205",
          zxk: "161",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          npj: "127",
          fbhd: "12",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        }, { 
          clxh: "17.5×6.00",
          lkfby: "205",
          zxk: "161",
          lkccjsm: "6-φ20.5",
          lkxz: "直孔/ISO",
          npj: "115",
          fbhd: "12",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        }, { 
          clxh: "17.5×6.00",
          lkfby: "225",
          zxk: "176",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "123",
          fbhd: "12",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        }, { 
          clxh: "17.5×6.00",
          lkfby: "203.2",
          zxk: "146",
          lkccjsm: "5-φ29",
          lkxz: "SR22/JAP",
          npj: "123/118/116",
          fbhd: "12/10",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        }, { 
          clxh: "17.5×6.00",
          lkfby: "208",
          zxk: "150",
          lkccjsm: "5-φ32",
          lkxz: "SR22/JAP",
          npj: "115",
          fbhd: "12",
          qmzxh: "PVR-51A",
          sylt: "215/70R17.5, 205/80R17.5, 215/70R17.5"
        },
      ]
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