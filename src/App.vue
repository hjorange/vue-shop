<template>
  <div id="app">
    <MyHeader/>
    <MyGoods/>

    <MyFooter/>

  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyGoods from './components/MyGoods.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  components:{
    MyHeader,
    MyGoods,
    
    MyFooter
  },
  data () {
    return {

    }
  },

  created () {

  },

  methods: {

  }
}
</script>

<style scoped>
#app{
  padding-top: 50px;
}
</style>
