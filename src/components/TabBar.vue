<template>
  <div id="tab-bar">
    <slot></slot>
  </div>  
</template>


<script>

export default {
  name:'TabBar'
}
</script>


<style scoped>
#tab-bar{
    display: flex;
    background-color: rgb(218, 218, 218);

    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;

    box-shadow: 0px -1px 2px rgba(0,0,0,0.2);
  }

  

</style>>
  
