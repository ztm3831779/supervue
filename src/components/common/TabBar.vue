<template>
  <div id="app">
    <div id="tab-bar">
<!--      <div class="tab-bar-item"></div>-->
<!--      <div class="tab-bar-item"></div>-->
<!--      <div class="tab-bar-item"></div>-->
<!--      <div class="tab-bar-item"></div>-->
      <slot></slot>
    </div>
  </div>
</template>

<script>


export default {
  name: 'TabBar',
  components: {

  }
}
</script>

<style scoped>
   #tab-bar{
     display: flex;
     background-color: #f6f6f6;
     position: fixed;
     left: 0;
     right: 0;
     bottom: 0;
     box-shadow: 0 -1px 1px rgba(100,100,100,.2);
   }

</style>
