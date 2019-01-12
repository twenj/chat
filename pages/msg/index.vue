<template>
    <view class="box">
      <view class="item">
        <text>空山灵雨</text>
      </view>
      <view class="item"></view>
      <view class="item"></view>
    </view>
</template>

<script>

</script>
<style>
  .box {
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    width: 100%;
  }
  .item {
    width:100%;
    height: 100upx;
    border-bottom: 1px solid rgba(0,0,0,.2);
  }
  .box:first-child {
    border-top: 1px solid rgba(0,0,0,.2);
  }
</style>