<template>
  <div id="app">
    <Homework/>
    <TableData/>
    <Inputs/>
  </div>
</template>

<script>
import Homework from './components/Homework.vue';
import TableData from './components/TableData.vue';
import Inputs from './components/Inputs.vue';

export default {
  name: 'app',
  components: {
    Homework,
    TableData,
    Inputs,
  },
};
</script>

<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align left
  color #2c3e50
  margin-top 60px
</style>
