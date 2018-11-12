<template>
    <view>
        123
        <slot name="header">i hope</slot>
        <slot name="joe"></slot>
    </view>
</template>

<script>
    export default {
        name : "myComponent",
        props : ["item"],
    }
</script>