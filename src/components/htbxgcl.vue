<template>
  <el-tabs
    v-model="activeName"
    type="border-card"
  >
    <el-tab-pane
      label="9.00V-20"
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
      label="8.25V-20"
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
      label="8.5-20"
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
      label="8.5~8.75-24"
      name="fourth"
    >
      <MyTable
        :data=data3
        :myurl="url3"
        :srcList="srcList3"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="7.50V-20"
      name="five"
    >
      <MyTable
        :data=data4
        :myurl="url4"
        :srcList="srcList4"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="7.50FL-20"
      name="six"
    >
      <MyTable
        :myurl="url5"
        :srcList="srcList5"
      >
      </MyTable>
    </el-tab-pane>
    <el-tab-pane
      label="7.00T-20"
      name="s"
    >
      <MyTable
        :data=data6
        :myurl="url6"
        :srcList="srcList6"
      >
      </MyTable>
    </el-tab-pane>
  </el-tabs>
</template>
<script>
import MyTable from "./htbxgcl/table";
export default {
  data() {
    return {
      activeName: "second",
      url: "http://www.zenixauto.com/uploads/allimg/141027/1-14102GJ611243.jpg",
      srcList: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102GJ611243.jpg"
      ],
      url1: "http://www.zenixauto.com/uploads/allimg/141027/1-14102GJ105H3.jpg",
      srcList1: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102GJ105H3.jpg"
      ],
      url2: "http://www.zenixauto.com/uploads/allimg/141027/1-14102GHR9532.jpg",
      srcList2: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102GHR9532.jpg"
      ],
      url3:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G2034T12.jpg",
      srcList3: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G2034T12.jpg"
      ],
      url4:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G14459553.jpg",
      srcList4: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G14459553.jpg"
      ],
      url5:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G13204A6.jpg",
      srcList5: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G13204A6.jpg"
      ],
      url6:
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G11FI55.jpg",
      srcList6: [
        "http://www.zenixauto.com/uploads/allimg/141027/1-14102G11FI55.jpg"
      ],
      data: [
        {
          clxh: "9.00V-20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "169",
          fbhd: "16/14",
          sylt: "１２.00R20"
        }
      ],
      data1: [
        {
          clxh: "8.25V-20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "162",
          fbhd: "16/14",
          sylt: "１1.00R20"
        },
        {
          clxh: "8.25V-20",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "162",
          fbhd: "16/14",
          sylt: "１1.00R20"
        },
        {
          clxh: "8.25V-20",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "162",
          fbhd: "16/14",
          sylt: "１1.00R20"
        },
        {
          clxh: "8.25V-20",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "162",
          fbhd: "16/14",
          sylt: "１1.00R20"
        },
        {
          clxh: "8.25V-20",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "162",
          fbhd: "16/14",
          sylt: "１1.00R20"
        }
      ],
      data2: [
        {
          clxh: "8.5-20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "166",
          fbhd: "16/14",
          sylt: "１２.00R200"
        }
      ],
      data3: [
        {
          clxh: "8.75-24",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "169/166",
          fbhd: "16/14",
          sylt: "１２.00R24"
        },
        {
          clxh: "8.5-24",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ＩＳＯ",
          npj: "169/166",
          fbhd: "16/14",
          sylt: "１２.00R24"
        }
      ],
      data4: [
        {
          clxh: "7.50V-20",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "160/156/151",
          fbhd: "16/14/12",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ISO",
          npj: "156/151/148",
          fbhd: "16/14/12",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "151/145",
          fbhd: "16/14/12",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "275",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ISO",
          npj: "152",
          fbhd: "14",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ26",
          lkxz: "直孔／ISO",
          npj: "149/106",
          fbhd: "14",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔／ISO",
          npj: "152/149",
          fbhd: "16/14",
          sylt: "10.00R20"
        },
        {
          clxh: "7.50V-20",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "152/150",
          fbhd: "16/14",
          sylt: "10.00R20"
        }
      ],
      data6: [
        {
          clxh: "7.00T-20",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "145/135",
          fbhd: "14/12",
          sylt: "9.00R20"
        },
        {
          clxh: "7.00T-20",
          lkfby: "275",
          zxk: "214",
          lkccjsm: "8-φ26",
          lkxz: "直孔/ISO",
          npj: "141/139",
          fbhd: "14/12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "145",
          fbhd: "14/12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "285.75",
          zxk: "222",
          lkccjsm: "10-φ32",
          lkxz: "SR22/JAP",
          npj: "149",
          fbhd: "14/12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "222.25",
          zxk: "164",
          lkccjsm: "6-φ32",
          lkxz: "SR22/JAP",
          npj: "130",
          fbhd: "12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "285",
          zxk: "221",
          lkccjsm: "8-φ32",
          lkxz: "SR22/JAP",
          npj: "153/150",
          fbhd: "14/12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "335",
          zxk: "281",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "140",
          fbhd: "14/12",
          sylt: "9.00R20"
        },{
          clxh: "7.00T-20",
          lkfby: "285.75",
          zxk: "220",
          lkccjsm: "10-φ26",
          lkxz: "直孔/ISO",
          npj: "151",
          fbhd: "14/12",
          sylt: "9.00R20"
        },
      ]
    };
  },
  methods: {
    
  },
  components: {
    MyTable
  }
};
</script>

<style>
</style>