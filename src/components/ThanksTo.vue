<template lang="pug">    
  div
    h1 Thanks To
    .thanks(style="padding: 6px;")
      template(v-for="thank in thanks")
        span {{ thank }}
        br
</template>

<script>
export default {
  name: 'SooProfile',
  props: {},
  data() {
    return { thanks: ['ㅈㄱㄹ', 'GN40', '이너'] };
  }
};
</script>