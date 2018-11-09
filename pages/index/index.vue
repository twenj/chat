<template>
	<view class="content">
        <text class="title">{{title}}</text>
        <text v-on:click="changeMessage">{{message}}</text>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
                message: "tom"
			};
		},
		methods() {

        }
	}
</script>

<style>
    @import "../common/common.css";
	.content {
		flex: 1;
		justify-content: center;
		align-items: center;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
