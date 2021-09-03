<template>
  <view class="content">
    <view>
      <text class="title">{{ title }}</text>
    </view>
    <view class="iconfont icon-Excel"></view>
    <view class="iconfont icon-File"></view>
    <view class="iconfont icon-Word"></view>
    <view class="iconfont icon-PPT"></view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      title: "字体图标使用例子",
    };
  },
  onLoad() {},
  methods: {},
};
</script>

<style>

.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.title {
  font-size: 100rpx;
  color: #444;
}
</style>
