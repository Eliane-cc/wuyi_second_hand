<template>
  <div class="message_row">
    <div class="message_contain">
      <div class="message_box">
        <icon-svg :icon-class="icon" class="test" :style="{color: iconColor}"/>
        <div>{{text}}</div>
      </div>
    </div>
  </div>
</template>

<script>
  import IconSvg from './IconSvg'
  export default {
    props: ['text','icon','iconColor'],
    name: "Message",
    components: {
       IconSvg
    }
  }
</script>

<style scoped>
  .message_row{
    margin-bottom: 12px;
    background-color: red;
  }
  .message_contain{
    display: inline-block;
    padding: 10px 14px;
    border-radius: 5px;
    box-shadow: 3px 2px 10px #cccccc;
  }
  .message_box{
    display: flex;
    flex-direction: row;
    align-items: center;
    align-content: center;
    font-size: 14px;
    color: #333333;
  }
  .test{
    margin-right: 5px;
  }
</style>