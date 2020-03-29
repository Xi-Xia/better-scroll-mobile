
<template>
    <div class="app">
        <div class="scroll-box">
            <scroll />
        </div>
    </div>
</template>

<script>
import scroll from 'components/Scroll.vue'
export default {
    name:'App',
    components:{
        scroll
    },
    data(){
        return{}
    }
}
</script>

<style lang="less" scoped>
    .app{
        padding: 5px;
        .scroll-box{
            padding: 4px 0;
            border-radius: 4px;
            border: solid 1px cyan;
        }
    }
</style>
