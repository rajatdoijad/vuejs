<template>
 
 <h1>Hello from home componenet</h1>
 <h2>{{data}}</h2>
 <h2>{{msg}}</h2>
 
  
</template>
<script>
export default {
      name:'homeComponent',
      props:{
        data: String,
        msg: String

      }


   
      }
   
      
    
   

</script>
<style scoped>
h1{
    color:orangered;
}
</style>
