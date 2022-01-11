<template>
  <div>
   <h1>Hello from root component</h1> 
   <my-header></my-header>
   <my-counter></my-counter>
   <my-counter></my-counter>
   <my-counter></my-counter>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Counter from './components/Counter.vue';

export default {
  components: {
    "my-header": Header,
    "my-counter":Counter
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
  margin-top: 60px;
}
</style>
