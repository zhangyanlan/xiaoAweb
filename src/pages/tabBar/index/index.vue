<template>
	<view class="content">
		<view class="yh_card">
			<view class="index-title">数据统计</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
			</view>
		</view>
		<view class="yh_card">
			<view class="index-title">数据统计</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
		
		</view>
		<view class="yh_card">
			<view class="index-title">数据统计</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
				<view class="flex-item ">B</view>
				<view class="flex-item ">C</view>
			</view>
			<view class="uni-flex uni-row">
				<view class="flex-item ">A</view>
			
			</view>
		</view>
	
       
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onNavigationBarButtonTap:function(e){
			console.log('object');
            console.log(JSON.stringify(e))
        },
		onLoad() {
	
		},
		methods: {
			
		}
	}
</script>

<style>

	.content {
		text-align: center;
		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
	.index-title{text-align: left;padding:10upx 30upx}
	.uni-flex{
		flex-wrap: wrap;
	}
	.flex-item {
		width: 33.3%;
		text-align: center;
	}
</style>
