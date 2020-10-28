<template>
  <div class="message_contain">
    <div class="message_box">
      <Icon />
      <div>{{text}}</div>
    </div>
  </div>
</template>

<script>
  import Icon from './Icon.vue'

  export default {
    props: ['text'],
    name: "Message",
    components: {
      Icon
    }
  }
</script>

<style scoped>
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

</style>