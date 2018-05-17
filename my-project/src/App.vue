<template>
  <div id="vue_det">
    <h1>site:{{site}}</h1>
    <h1>url:{{url}}</h1>
    <h1>{{details}}</h1>
  </div>
</template>

<script>
new Vue(
{
  el:'#vue_det',
  data:{
    site:"JunYiZzz的第一个vue",
    url:"www.baidu.com",
  },
  methods:{
    details:function(){
      return  this.site+"-233333";
    }
  }
})
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
