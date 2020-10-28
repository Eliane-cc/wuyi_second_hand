<template>
  <div class="icon_contain">
    <img src="../assets/info-circle-fill.svg" class="icon">
  </div>
</template>

<script>
  export default {
    name: "Icon"
  }
</script>

<style scoped>
  .icon_contain{
    display: flex;
    align-content: center;
    align-items: center;
  }
  .icon{
    width: 18px;
    height: 18px;
    display: inline-block;
    margin-right: 6px;
  }
</style>