<template>
  
  <HelloWorld msg="Welcome to Your Vue.js App76567"/>
  <Home />
  <Home />
  <binding />
  <Get_input/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'
import binding from './components/binding.vue'
import Get_input from './components/Get_input.vue'
export default {
    name: 'App',
   components: {
    HelloWorld,
    Home,
      binding,Get_input
    ,
  }
}
</script>

