<template>
	<view class="content">
		<!-- <view class="uni-list"> -->
			我是首页
		<!-- </view> -->
		
		<!-- <text class="icon iconfont icon-xiaoxi1">111</text> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello1111',
				list:[
					{title:"zs",content:'ffff'},
					{title:"ls",content:'ssss'}
					]
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
