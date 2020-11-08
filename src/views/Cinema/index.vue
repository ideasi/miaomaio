<template>
  <div id="main">
    <Header title="喵喵影院" />
    <div id="content">
      <div class="cinema_menu">
        <div class="city_switch">
          全城 <i class="iconfont icon-lower-triangle"></i>
        </div>
        <div class="brand_swtich">
          品牌 <i class="iconfont icon-lower-triangle"></i>
        </div>
        <div class="feature_switch">
          特色 <i class="iconfont icon-lower-triangle"></i>
        </div>
      </div>
      <CiList />
    </div>
    <TabBar />
  </div>
</template>
<script>
import Header from "@/components/Header";
import TabBar from "@/components/TabBar";
import CiList from "@/components/CiList";
export default {
  name: "Cinema",
  components: {
    Header,
    TabBar,
    CiList
  },
};
</script>
<style>
</style>