<template lang="html">
    <div :class="$style.header">
        <span :class="$style.left">
            登录|注册
        </span>
        <btn :class="$style.right">APP下载</btn>
    </div>
</template>

<script>
 import btn from '../core/btn.vue'
export default {
     components: {
         btn
     }
}
</script>

<style lang="scss" module>
.header{
    color: #666;
    height:100px;
    line-height: 100px;
    background: #fff url("https://m.jr.jd.com/spe/qyy/main/images/jr-logo.png") center center no-repeat;
    background-size: auto 50%;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 100;
    .left{
        font-size: 28px;
        height: 30px;
        line-height: 30px;
        margin:17px 0 0 18px;
    }
    .right{
        float: right;
        font-size:24px;
        border-width:0;
        height:56px;
        line-height: 56px;
        min-width:120px;
        padding: 0;
        border-radius: 4px;
        margin:28px 24px 0 0;
    }
}
</style>
