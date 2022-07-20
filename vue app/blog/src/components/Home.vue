<template>
    <h1 v-on:mousemove="getConsole() "> Home component</h1>
    <button v-on:dbclick ="test()">Click Me</button>
    <h2>{{count}}</h2>
    </template>
<script>
    export default{
        name:'HomeW',
        data(){
            return{
                count:0
            }
        },
        methods:{
            test(){
                alert("function called");
            },
            getConsole()
            {
                console.warn("function called");
            }
        }
       
    }
</script>
<style scoped>
h1{
    color: aqua;
}
</style>