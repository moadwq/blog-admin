<template>
  <div class="dashboard-container">
    <div class="dashboard-text">
      mohan博客
    </div>
    <div>
      <p>作者个人邮箱：1485804541@qq.com</p>
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'
export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
