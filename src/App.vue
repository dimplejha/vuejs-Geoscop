<template>
<div class="container">
  <HeaderMust title="dimple"/>
  <TaskList :task="task" />
  <!-- <button v-on:click="show=!show">Toogle</button> -->
  <!-- <beforeUnmounted v-if="show"/> -->

</div>

</template>

<script>

import HeaderMust from "./components/HeaderMust.vue"
import TaskList from "./components/TaskList.vue" 

// import beforeUnmounted from "./components/beforeUnmounted"


export default {
  name: 'App',
  components: {
   HeaderMust,
   TaskList
  //  beforeUnmounted
  },


  data(){
    return{
      // show:true,
      task:[]
    }
  },
  created(){
    this.task=[{
      id:1,
      text:"Docors appoitment",
      day:"march 1st 2019",
      remainder:true,
    },
    {
      id:2,
      text:"buy medicine",
      day:"may 1st 2020",
      remainder:true,
    },
    {
      id:3,
      text:"pay money",
      day:"june 1st 2021",
      remainder:false,
    },
    ]
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



<!-- today is solve many html css javascript git mcq trick questions with different website -->
