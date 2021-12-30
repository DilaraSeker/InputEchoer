<template>
  <div>
    <span>Input message is:</span>
    <p >{{ message }}</p>
    <br>
    <textarea v-model="message" placeholder="Write your messsage"></textarea>
  </div>
</template>

<script>
  export default {
    name: 'Input',
    data(){
      return{
        message: ''
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>