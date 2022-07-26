<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">-->
   <HelloWorld msg="Welcome to Your Vue.js App"/> 
  
    
    <home  msg="hii from anil"/>

</template>


<script>
import HelloWorld from './components/HelloWorld.vue'
import home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    home,
  }
}
</script>




