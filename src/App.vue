<template>
  <div id="app">
    <h3>黑马头条</h3>
    <div>
      <i class="toutiao toutiao-dianzan"></i>
    </div>
    <router-view/>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>
<script>
export default {
  name: 'App'
}
</script>
<style lang="less">
</style>
