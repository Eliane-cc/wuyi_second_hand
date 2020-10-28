<template>
  <!--  Message组件的使用-->
  <Message text="这是一条提示信息" icon="check-circle-fill" icon-color="#1890FF"/>

</template>

<script>
import Message from './components/Message.vue'

export default {
  name: 'App',
  components: {
    Message
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
