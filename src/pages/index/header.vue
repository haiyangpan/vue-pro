<template>
 <div class="header">
    <div class="back iconfont">&#xe66a;</div>
    <div class="search">
    	<span class="iconfont search-icon">&#xe627;</span>请输入搜索内容说
    </div>
    <div class="city"></div>
 </div>
</template>

<script>
export default {
  name: 'index-header'
}
</script>

<style lang='stylus' scoped>
   @import '../../assets/stylus/varibles.styl';
   .header
     display: flex
     height: .88rem
     background: $bgColor
     .back
       width: .58rem
       text-align: center
       line-height: .88rem
       color: #fff
     .search
     	width 5.18rem
     	height .6rem
     	margin .14rem 0
     	line-height .6rem
     	background #fff
     	border-radius .14rem
     	padding-left .2rem
     	color #ccc
     	.search-icon	
     		width .2rem
     		height .2rem
</style>
