<template>
    <h1>Two Way Binding</h1>
        <input type="text" v-model="count"/>
        <h2>{{count}}</h2>
    </template>
<script>
    export default{
        name:'HomSeW',
        data(){
            return{
                count:4545
            }
        }
       
       
    }
</script>
<style scoped>
h1{
    color: aqua;
}
</style>