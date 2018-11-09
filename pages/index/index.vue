<template>
	<view class="content">
        <select v-model="selected">
            <option value="1">一</option>
            <option value="2">二</option>
            <option value="3">三</option>
        </select>
	</view>
</template>

<script>
    // import myComponent from "../../components/myComponent"
	export default {
	    elements: "#example-3",
		data() {
			return {
			    select : ''
			};
		},
		methods: {
            showAlert: function () {
                console.log(111)
            }
        },
        // components: {
		//     myComponent
        // }
	}
</script>

<style>
    @import "../../common/css/common.css";
	.content {
		flex: 1;
		justify-content: center;
		align-items: center;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
    
    input {
        background: #f00;
    }
</style>
