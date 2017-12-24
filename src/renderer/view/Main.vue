<template>
  <div class="jt-container">
    <div class="jt-head">
      <div class="jt-head-time">{{playTime}}</div>
      <div class="jt-head-name">{{playMusic}}</div>
      <div class="jt-head-time">{{totalTime}}</div>
    </div>
    <div class="jt-body"></div>
    <div class="jt-foot"></div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
      playMusic: '',
      playTime: '0:00',
      totalTime: '0:00'
    }
  }
}
</script>

<style scoped>
.jt-container {
  display: flex;
  align-items: center;
}

.jt-head {
  display: flex;
}

.jt-head-time {
  
}
</style>
