<template>

<button v-on:click="onClick()" :style="{background:color}" class="btn" >{{text}}</button>


  
</template>

<script>


export default {
    name:"ButtonFirst",
    props:{
        text:String,
        color:String,

    },
    methods:{
    onClick()
    {
        console.log("running")
        

    }
    }
}
</script>

<style>

</style>