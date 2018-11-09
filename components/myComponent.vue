<template>
    <view>
        {{item.title}}
    </view>
</template>

<script>
    export default {
        name : "myComponent",
        props : ["item"],
    }
</script>