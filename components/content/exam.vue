<template>
	<content>
		<view slot="left">真题讲解</view>
		<view slot="right_top">知识要点习题精讲</view>
		<view slot="right_bottom">模拟试题详细解析</view>
	</content>
</template>

<script>
	import content from "../common/content.vue"
	export default{
		data(){
			return{
				
			}
		},
		components:{
			content
		}
	}
</script>

<styles scoped>
</style>