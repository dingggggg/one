<template>
    <div class="header">
        <i class="header-category"></i>
        <div class="header-one">
            <span>一个</span>
        </div>
        <i class="header-search"></i>
    </div>
</template>

<script>
export default {
    name: 'header',
    data: function (){
        return {
            show:true
        }
    }
}
</script>

<style>
.header{
    height: 4rem;
    width: 100%;
    text-align: center;
    line-height: 4rem;
    border-left: 1px solid #ddd;
    border-right: 1px solid #ddd;
}
.header-one{
    display: inline-block;
    font-size: 3rem;
}
.header i{
    display: inline-block;
    width: 4rem;
    height: 4rem;
}
.header-category {
    background: url(/static/images/Category.png) no-repeat;
    background-size: 100% 100%;
    float: left;
    /*background-repeat: no-repeat;*/
}
.header-search {
    background: url(/static/images/search.png) no-repeat;
    background-size: 100% 100%;
    float: right;
    /*background-repeat: no-repeat;*/
}
</style>
