<template>
<div class="container">
  <HeaderMust title="dimple"/>

</div>

</template>

<script>

import HeaderMust from "./components/HeaderMust.vue"


export default {
  name: 'App',
  components: {
   HeaderMust
  },


  data(){
    return{
      task:[]
    }
  }

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=poppins:wght@300;400&display=swap');
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  font-family: 'Poppins',sans-serif;
}
.container{
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}
.btn{
  display: inline-block;
  background: #000;
  color: #fff;
  border:none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}
</style>
