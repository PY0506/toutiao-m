<template>
  <div id="app">
    <!-- 路由出口 -->
    <router-view />
    <h1>头条</h1>
    <div>
      <i class="toutiao toutiao-zuopin"></i>
      <van-button type="default">默认按钮</van-button>
      <van-button type="primary">主要按钮</van-button>
      <van-button type="info">信息按钮</van-button>
      <van-button type="warning">警告按钮</van-button>
      <van-button type="danger">危险按钮</van-button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="less"></style>
