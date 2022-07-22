<template>
  <h1>unmounted</h1>

</template>

<script>
export default {
    name:"beforUnmounted",
    beforeUnmount(){
        console.log("1")
    },
    unmounted(){
        console.log("2")
    }


}
</script>

<style>

</style>