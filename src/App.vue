<template>
  <div id="app">
    <v-header :index="2"></v-header>
  </div>
</template>
<script>
import header from './components/header/header.vue'
import Vue from 'vue'
import axios from 'axios'
import Vueaxios from 'vue-axios'
Vue.use(Vueaxios, axios)
export default {
  components: {
    'v-header': header
  },
  created () {
  }
}
</script>
<style lang="stylus" rel="stylesheet/stylus">
  @import "common/font-icon/style.css"
  @import "common/stylus/border-1px/index.styl"
  @import "common/stylus/global.styl"
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
