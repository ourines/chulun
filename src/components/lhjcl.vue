<template>
  <el-tabs
    v-model="activeName"
    type="border-card"
  >
    <el-tab-pane
      label="22.5×11.75"
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
      label="22.5×9.00"
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
      label="22.5×8.25"
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
      label="17.5×6.00"
      name="fourth"
    >
      <MyTable
        :data=data3
        :myurl="url3"
        :srcList="srcList3"
      >
      </MyTable>
    </el-tab-pane>
  </el-tabs>
</template>
<script>
import MyTable from "./lhjcl/table";
export default {
  data() {
    return {
      activeName: "second",
      url:
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103K6411.jpg",
      srcList: [
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103K6411.jpg"
      ],
      url1:
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103601113.jpg",
      srcList1: [
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103601113.jpg",
        "http://www.zenixauto.com/uploads/allimg/151113/1-15111310344W49.jpg"
      ],
      url2:
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103205a3.jpg",
      srcList2: [
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113103205a3.jpg",
        "http://www.zenixauto.com/uploads/allimg/151113/1-15111310214L42.jpg",
        "http://www.zenixauto.com/uploads/allimg/151113/1-15111310214L42.jpg"
      ],
      url3:
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113101U9442.jpg",
      srcList3: [
        "http://www.zenixauto.com/uploads/allimg/151113/1-151113101U9442.jpg"
      ],
      data: [
        {
          ggxh: "22.5×11.75",
          sc: "斯太尔",
          cz: "6061-T6",
          wpj: "0",
          lskgsjzj: "10-ф26",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "24.5",
          qmzxh: "TR570C",
          sylt: "385/65R22.5"
        }
      ],
      data1: [
        {
          ggxh: "22.5×9.00",
          sc: "斯太尔",
          cz: "6061-T6",
          wpj: "177",
          lskgsjzj: "10-ф26/φ32",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "23.8/25",
          qmzxh: "V3-20-1AA",
          sylt: `12R22.5， 295/80R22.5， 315/80R22.5`
        },
        {
          ggxh: "22.5×9.00外置式",
          sc: "斯太尔",
          cz: "6061-T6",
          wpj: "177",
          lskgsjzj: "10-ф26/φ32",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "23.8/25",
          qmzxh: "MS70-7",
          sylt: `12R22.5， 295/80R22.5， 315/80R22.5`
        },
        {
          ggxh: "22.5×9.00",
          sc: "斯太尔 韩国",
          cz: "6061-T6",
          wpj: "139",
          lskgsjzj: "10-ф26",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "24/25",
          qmzxh: "V3-20-1AA",
          sylt: `12R22.5， 295/80R22.5， 315/80R22.5`
        },
        {
          ggxh: "22.5×9.00",
          sc: "乘龙王",
          cz: "6061-T6",
          wpj: "177",
          lskgsjzj: "10-ф26",
          lmz: "直孔",
          fby: "ф285.75",
          zk: "ф220.1",
          lfhd: "23.8/25",
          qmzxh: "TR555D",
          sylt: `12R22.5， 295/80R22.5， 315/80R22.5`
        }
      ],
      data2: [
        {
          ggxh: "22.5×8.25",
          sc: "斯太尔",
          cz: "6061-T6",
          wpj: "168",
          lskgsjzj: "10-ф26/φ32",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "23.8/25",
          qmzxh: "V3-20-1AA",
          sylt: `11R22.5， 275/80R22.5`
        },
        {
          ggxh: "22.5×8.25",
          sc: "153",
          cz: "6061-T6",
          wpj: "168",
          lskgsjzj: "10-ф32.5",
          lmz: "SR22",
          fby: "ф285.75",
          zk: "ф222",
          lfhd: "23.8/25",
          qmzxh: "TR555D",
          sylt: `11R22.5， 275/80R22.5`
        },
        {
          ggxh: "22.5×8.25",
          sc: "乘龙王",
          cz: "6061-T6",
          wpj: "168",
          lskgsjzj: "10-ф26",
          lmz: "直孔",
          fby: "ф285.7",
          zk: "ф220.1",
          lfhd: "23.8/25",
          qmzxh: "TR555D",
          sylt: `11R22.5， 275/80R22.5`
        },
        {
          ggxh: "22.5×8.25",
          sc: "小平面大三",
          cz: "6061-T6",
          wpj: "168",
          lskgsjzj: "8-ф32.5",
          lmz: "SR22",
          fby: "ф285",
          zk: "ф221",
          lfhd: "23.8/25",
          qmzxh: "TR555D",
          sylt: `11R22.5， 275/80R22.5`
        },
        {
          ggxh: "22.5×8.25 外置式",
          sc: "斯太尔",
          cz: "6061-T6",
          wpj: "168",
          lskgsjzj: "8-ф32.5",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "23.8/25",
          qmzxh: "MS70-7",
          sylt: `11R22.5， 275/80R22.5`
        },
        {
          ggxh: "22.5×8.25",
          sc: "斯太尔 韩国",
          cz: "6061-T6",
          wpj: "129",
          lskgsjzj: "10-ф26",
          lmz: "直孔",
          fby: "ф335",
          zk: "ф281.2",
          lfhd: "24/25",
          qmzxh: "V3-20-1AA",
          sylt: `11R22.5， 275/80R22.5`
        }
      ],
      data3: [
        {
          ggxh: "17.5×6.00",
          sc: "跃进",
          cz: "6061-T6",
          wpj: "128",
          lskgsjzj: "6-ф26",
          lmz: "直孔",
          fby: "ф205",
          zk: "ф161",
          lfhd: "19",
          qmzxh: "TR554C",
          sylt: "215/75R17.5， 8R17.5"
        },
        {
          ggxh: "17.5×6.00",
          sc: "宇通",
          cz: "6061-T6",
          wpj: "128",
          lskgsjzj: "6-ф26",
          lmz: "直孔",
          fby: "ф222.25",
          zk: "ф174",
          lfhd: "19",
          qmzxh: "TR554C",
          sylt: "215/75R17.5， 8R17.5"
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