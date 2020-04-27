<template>
  <div class="app">
    <h2 @click="sayHEllo">标题</h2>
  </div>
</template>

<script>
export default {
methods: {
  sayHello(){
    alert('hello')
  }
},
}
</script>

<style>
.app{
  background-color: skyblue;
}
</style>