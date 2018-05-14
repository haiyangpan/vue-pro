<template>
 <div class="header">
    <div class="back">
      &lt;
    </div>
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
</style>
