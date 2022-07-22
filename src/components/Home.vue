<template>
   <h1>Get the input field value</h1>
   <h3>Technology</h3>
    <label for="java">java</label>
    <input type="checkbox" value="java" v-model="technology" id="java">

    <label for="php">php</label>
    <input type="checkbox" value="php" v-model="technology" id="php">
    
    <label for="node">node</label>
    <input type="checkbox" value="node" v-model="technology" id="node">
     <br/><br/>
     <h3>who am i</h3>
     <label for="student">Student</label>
    <input type="radio" value="student"  v-model="who" name="who" id="student">
     
      <label for="developer">Developer</label>
    <input type="radio" value="developer" v-model="who" name="who"  id="developer">
     
     <br>
      
    <h3>Selected Technology1: {{technology}}</h3>
  
  
  
  
</template>
<script>
export default {
      name:'homeComponent',
      data()
      {
        return {
            technology: [],
            who: null
        }
      }
   
      }
    
   

</script>
<style scoped>
h1{
    color:orangered;
}
</style>