<template lang="pug">
  #app
    .title-soo
      h1 #soOtheIEMChamp
    el-main
      el-row
        el-col(:xs="0" :sm="4" :md="6")
            span &nbsp;
        el-col(:xs="24" :sm="16" :md="12" style="text-align: justify;")
          span.main-text 스타크래프트2 프로게이머 어윤수 선수의 생애 첫 프리미어급 리그 우승을 기념하기 위해 우주전쟁 마이너 갤러리(구 스타크래프트2 갤러리)의 팬들이 돈을 모아 지하철 2호선 삼성역에 광고를 걸게 되었습니다. 데뷔로부터 3,540일, 첫 준우승으로부터 1,961일, 프리미어급 대회 7번의 준우승 끝에 마침내 따낸 어윤수 선수의 값진 첫 우승을 함께 축하해주세요!
        el-col(:xs="0" :sm="4" :md="6")
          span &nbsp;

      hr

      el-row
        el-col(:xs="0" :sm="4" :md="6")
          span &nbsp;
        el-col(:xs="24" :sm="16" :md="12")
          SooProfile
        el-col(:xs="0" :sm="4" :md="6")
          span &nbsp;
      
      hr

      el-row
        el-col(:xs="0" :sm="4" :md="6")
          span &nbsp;
        el-col(:xs="24" :sm="16" :md="12")
          ThanksTo
        el-col(:xs="0" :sm="4" :md="6")
          span &nbsp;
</template>

<script>
import SooProfile from './components/SooProfile.vue';
import ThanksTo from './components/ThanksTo.vue';

export default {
  name: 'app',
  components: {
    SooProfile,
    ThanksTo
  }
};
</script>

<style src="./assets/style.less" lang="less">
</style>
