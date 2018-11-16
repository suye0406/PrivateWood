<template>
    <div>
        <unpayheader-com></unpayheader-com>
        <empty-com></empty-com>
        <!-- <unpaygoodslist-com></unpaygoodslist-com> -->
        <likeGoods-com></likeGoods-com>
        <router-view></router-view>
    </div>
</template>

<script>
import unpaygoodslist from './unpay-goodslist'
import likeGoods from './likeGoods'
import unpayheader from './unpay-header'
import empty from './empty'
export default {
    components: {
        'unpaygoodslist-com': unpaygoodslist,
        'likeGoods-com': likeGoods,
        'unpayheader-com': unpayheader,
        'empty-com': empty
    }
}
</script>

<style lang="scss">
    
</style>