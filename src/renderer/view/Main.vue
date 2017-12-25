<template>
  <div class="jt-container">
    <div class="jt-head">
      <h3 class="text-center">{{playMusic}}</h3>
    </div>
    <div class="jt-body">
      <div class="jt-wave"></div>
      <div class="jt-progress-bar">
        <div class="jt-progress"></div>
      </div>
    </div>
    <div class="jt-foot jt-flex">
      <div class="jt-foot-list">
        <a href="javascript:;">
          <i class="iconfont icon-list"></i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
      playMusic: 'MUSIC NAME',
      playTime: '0:00',
      totalTime: '0:00'
    }
  }
}
</script>

<style scoped>
.jt-container {
  display: flex;
  flex-direction: column;
  height: 100%;
}

.jt-flex {
  display: flex;
}

.jt-content-center {
  justify-content: center;
}

.jt-content-space-between {
  justify-content: space-between;
}

.jt-content-space-around {
  justify-content: space-around;
}

.jt-head {
  padding: 1rem;
}

.jt-foot {
  margin-top: auto!important;
}

.text-center {
  text-align: center;
}
</style>
