<template>

    <div class="tab-bar-item">
      <div v-if="!isactive"><solt name="item-icon"></solt></div>
      <div v-else><solt name="item-icon-active"></solt></div>
      <div :class="{active: isactive}"><solt name="item-text"></solt></div>
    </div>

</template>

<script>
export default {
  name: 'TabBarItem',
  data(){
     return {
       isactive: false,
     }
  }

}
</script>

<style>
  .tab-bar-item{
     flex: 1;
     text-align: center;
     height: 49px;
  }
  .tab-bar-item img{
    width: 24px;
    height: 24px;
  }

</style>
