<template>
  <h1> Home Component {{"anil".length}}</h1>
  <button v-on:click="getName('Button 1 clicked')">Click Me</button>
   <button v-on:mousemove="getName('Button 1 clicked')">Click Me</button>
  
  
  <h1>Name {{getName("Naruto")}}</h1>
</template>
<script>
export default {
      name:'homeComponent',
      data(){
        return{
            email:'anil@joke.com',
            mobile:234567890,
            getName:function(){
              alert("Hello ");
            }
        }
      }
}
</script>
<style scoped>
h1{
    color: orangered;
}
</style>