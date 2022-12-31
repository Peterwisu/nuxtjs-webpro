<template>

  <div>

    <div class='container'>

      <div class='row mx-5 my-5'>

        <div class='col-12'>
          <p class='title'>My Project</p>
        </div> 


        <div class='col-12 my-5 '>

          <h3 class="section">My Thesis</h3>
             <Card v-bind:items=uni /> 
        </div>

        <div class='col-12 my-5'>

          <h3 class="section">My own projects</h3>
          <Card v-bind:items=uni /> 
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


import Card from './Card.vue'

export default{

  name : "index",

  components : {

    Card
  },

  data(){

    return {

    uni : [

    {
      "university" : "Surrey",
      "id" : 1,
      "name" : "OOP in Java",
      "content" : "This is an assingment for COM1027 Fundamental Programming" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM1027-Assignment"
              }
    },
     {
      "university" : "Surrey",
      "id" : 2,
      "name" : "Web & Database in PHP and MySQL",
      "content" : "This is an assingment for COM1025 Web and Data " ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM1025-Assignment"
              }
    },
     {
      "university" : "Surrey",
      "id" : 3,
      "name" : "SE in Java",
      "content" : "This is an assingment for COM1028" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM1028-Assignment"
              }
    },
     {
      "university" : "Surrey",
      "id" : 4,
      "name" : "CUDA Programming in C/C++",
      "content" : "This is an assingment for COM2039" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM2039-Assignment"
              }
    },
     {
      "university" : "Surrey",
      "id" : 5,
      "name" : "Hangman game in ARM assembly",
      "content" : "This is an assingment for COM1031" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM1031-CW-Hangman-ARM-Assembly"
              }
    },
     {
      "university" : "Surrey",
      "id" : 6,
      "name" : "Web application in Ruby",
      "content" : "This is an assingment for COM2025" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM2025-Assignment-Coursework"
              }
    },
     {
      "university" : "Surrey",
      "id" : 7,
      "name" : "Real-time video transfer protocol",
      "content" : "This is an assingment for COM2022" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM2022_Assignment_extension"
              }
    },
     {
      "university" : "Surrey",
      "id" : 8,
      "name" : "Bussiness Analytics using R",
      "content" : "This is an assingment for COM3018" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM3018-Assignment-PBA"
              }
    },
     {
      "university" : "Surrey",
      "id" : 9,
      "name" : "Cells classification",
      "content" : "This is an assingment for COM2028" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM2028-Assignment-AI"
              }
    },
     {
      "university" : "Surrey",
      "id" : 10,
      "name" : "Evolutionary Compuation for Image classification",
      "content" : "This is an assingment for COM3031" ,
      "link" : {
                
                "github" : "https://github.com/Peterwisu/COM3031-CI"
              }
    }
  ] 
    }

  }
   


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
