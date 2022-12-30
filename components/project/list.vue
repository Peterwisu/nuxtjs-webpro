<template>
  <div>
    <div class='container'> 
      <div class="row">

        <div v-for="item in items" class='col-md-4'> 
          <b-card
            v-bind:title="item.name"
            title-tag="h4"
            img-src="https://picsum.photos/600/300/?image=25"
            img-alt="Image"
            img-top
            tag="article"
            body-class="card-body"
            style="max-width: 20rem; border-color : var(--border); border-width: 2px ;background-color : var(--hover);"
            class="mb-2">
            <b-card-text>
              {{item.content}}
            </b-card-text>
            <b-button v-bind:href="item.link.github" active-class="card-body"variant="primary">
              <img class="img-fluid icon" src="~/assets/icons/github-mark-white.svg" /> 
              gtihub
            </b-button>
          </b-card>
        </div>

      </div>
    </div>
  </div>
</template>


<script>


//import axios from 'axios'

import fetch from 'node-fetch'

export default{

  data() {
    return {
      items:[

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

h4 {

  color : var(--yellow);
  font-weight : bold;
}

.card-body{

}

.btn-primary{

  border: none;
  background-color : var(--bg);
  font-weight : bold;
  color : var(--green);

}


.icon{
  width:22px;
  height:22px;
}

</style>
