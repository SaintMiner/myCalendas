<template>
  <div id="app">
    <h1>LOADING COMPLETE</h1>
    <calendar></calendar>    
  </div>
</template>

<script>

import calendar from './components/calendar.vue';

export default {
  name: 'app',
  components: {
    calendar
  },

  
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;  
}
</style>
