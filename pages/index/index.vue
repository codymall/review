<template>
	<view class="main">
		<view class="main_top"></view>
		<Knowledge></Knowledge>
		<Exam></Exam>
	</view>
</template>

<script>
	import Knowledge from "@/components/content/knowledge.vue"
	import Exam from "@/components/content/exam.vue"
	export default {
		data() {
			return {

			}
		},
		components: {
			Knowledge,
			Exam
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style scoped>
	.main_top {
		width: 100vh;
		height: 260rpx;
		background-color: black;
	}
</style>
