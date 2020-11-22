<template>
  <div class="tab-page">
      <image-edit></image-edit>
  </div>
</template>

<script>
import ImageEdit from './ImageEdit/index' // 图片管理
export default {
  name: 'tabPage',
  components: {
    ImageEdit
  },
  computed: {
  },
  data () {
    return {
      choiseName: '设备选择'
    }
  },
  created () {
  },
  methods: {
  }
}
</script>

<style lang="scss" scoped>
.el-tabs--border-card {
    box-shadow: none;
}
.tab-page {
    width: 100%;
    margin: 30px 30px;
    height: 100%;
  .tab-page-row {

  }
}
</style>
