<template>
<header>
<h1>{{title}}</h1>

<ButtonFirst  text="update"  color="Green"/>


<FotterEnd/>
</header>
    
</template>

<script>

import ButtonFirst from "./ButtonFirst.vue"

 export default{
    name:'HeaderMust',
    props:{
      title:String,
    },
 components:{
    
    ButtonFirst,
    
}
 }

</script>






