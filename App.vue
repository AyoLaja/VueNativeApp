<template>
  <view class="container">
    <text class="text-color-primary">Jintus App</text>
    <phone-header></phone-header>
    <phone-body></phone-body>
  </view>
</template>

<script>
  import PhoneBody from './components/PhoneBody.vue'
  import PhoneHeader from './components/PhoneHeader.vue'

  export default {
    components: {
      PhoneBody,
      PhoneHeader
    }
  }
</script>

<style>
  .container {
    background-color: white;
    align-items: center;
    justify-content: center;
    flex: 1;
  }
  
  .text-color-primary {
    color: blue;
  }
</style>