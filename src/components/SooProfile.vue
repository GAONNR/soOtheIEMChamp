<template lang="pug">    
  el-card(style="margin: 24px; margin-top: 32px;")
    h1 soO | 어윤수
    img.image(src="../assets/logo.jpg")
    div(style="padding: 20px;")
      div(style="display: inline-block; width: 100%;")
        el-row
          el-col(:span="10" style="text-align: right;") 이름&nbsp&nbsp&nbsp;
          el-col(:span="12" style="text-align: left;")
            strong 어윤수 (Eo yoon-soo)
        el-row(style="width: 100%;")
          el-col(:span="10" style="text-align: right;") 생년월일&nbsp&nbsp&nbsp;
          el-col(:span="12" style="text-align: left;")
            strong 1992년 9월 24일
        el-row(style="width: 100%;")
          el-col(:span="10" style="text-align: right;") 종족&nbsp&nbsp&nbsp;
          el-col(:span="12" style="text-align: left;")
            strong 저그
        el-row(style="width: 100%;")
          el-col(:span="10" style="text-align: right;") 소속&nbsp&nbsp&nbsp;
          el-col(:span="12" style="text-align: left;")
            strong Chivo SC
      div(style="text-align: center; margin-top: 40px;")
        h3 &#8722; 경력 &#8722;
      div(style="text-align: left; display: inline-block;")
        li 2013 WCS Korea Season 3 준우승 (vs 백동준, 2:4)
        li 2014 HOT6 GSL Season 1 준우승 (vs 주성욱, 3:4)
        li 2014 HOT6 GSL Season 2 준우승 (vs 김도우, 2:4)
        li 2014 HOT6 GSL Season 3 준우승 (vs 이신형, 2:4)
        li 2017 HOT6 GSL Season 1 준우승 (vs 김대엽, 2:4)
        li 2017 HOT6 GSL Season 2 준우승 (vs 고병재, 2:4)
        li 2017 WCS Global Finals 준우승 (vs 이병렬, 2:4)
        li 
          strong(style="color: #E6A23C;") IEM Season XIII - Katowice 우승 (vs 김대엽, 4:2)
</template>

<script>
export default {
  name: 'SooProfile',
  props: {}
};
</script>