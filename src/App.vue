<template>
  <div id="app">
    <Input/>
  </div>
</template>

<script>
import Input from './components/Input.vue'

export default {
  name: 'App',
  components: {
    Input
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #000000;
  margin-top: 60px;
  background-color: rgb(174, 167, 243);
}
</style>
