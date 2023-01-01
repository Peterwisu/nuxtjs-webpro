<template>

  <div>
    
    <div class='container'>

      <div class='row mx-5 my-5'>

        <div class='col-12'>
          <p class='title'>My Project</p>
        </div> 

        
        <div class='col-12 my-5 '>

          <h3 class="section">My Thesis</h3>
            <Card v-bind:items=thesis /> 
        </div>

        <div class='col-12 my-5'>

          <h3 class="section">My own projects</h3>
          <Card v-bind:items=own /> 
        </div>


        <div class='col-12 my-5'>
          <h3 class="section">University Assignments</h3>
          <Card v-bind:items=uni /> 
        </div>



      </div>

    </div>

  </div>


</template>


<script>




import university from "~/pages/project/university.js"
import thesis from "~/pages/project/thesis.js"
import own from "~/pages/project/own.js"


import Card from './Card.vue'

export default{

  name : "index",

  components : {

    Card
  },

  data(){

    return {

    uni : university.data,
    thesis :thesis.data,
    own  : own.data
    }

  },
 // async fetch(){

 //   this.uni = await  fetch('http://127.0.0.1:8000/projects/university').then(res=>res.json())
 //   this.thesis = await fetch('http://127.0.0.1:8000/projects/thesis').then(res=>res.json())
 //   this.own = await fetch('http://127.0.0.1:8000/projects/own').then(res=>res.json())
 //   this.own = await fetch('http://127.0.0.1:8000/projects/own').then(res=>res.json())
 //   

 // }
   


}


</script>


<style scoped>

.title {


  color : var(--green);
  font-size : 50px;
  font-weight : bold;

}

.section {

  color: var(--red);
  font-weight: bold;
  margin-bottom : 40px


}


</style>
