<template>

  <div>
    <div class='container '>
      
      
      <div class='row mt-5 mx-5 '>

        <div class='col-md-8'>

          
          <p class='title'> About Me </p>     

      
          <h2>My name is <p class="highlight-red">Wish Suharitdamrong, </p></h2>
          <h3> I am  a computer science student specialized in the area of Artificial Intelligence (AI). My main interests in AI are Machine learning and Computer Vision.</h3>

          

        </div>

        <div class='col-md-4 col-img'>

          <!----<img :src='image' class="img-fluid rounded">--->


          <!---<b-img :src='image' clalss='img' fluid-grow rounded="circle"></b-img>--->
          <img src='~/assets/img/profile.jpg' class='img-fluid rounded-circle' >

          

        </div>

      </div>
      <div class='row mx-5 mt-4'>
        <div class='col-md-12'> 


          <p>I am  currently studying my final year undergradute in BSc computer science at University of Surrey.</p> 

          <p>My first impression in AI was when OpenAI release model that can actually play video games named Dota2, as someone who was addicted to that game for almost decade that was really amaze me. Moreover machine learning, is the first area in my studies that change my perspective and though about mathematics. It allows me to gain more interest in mathematics and specially 
           I enjoyed most of my time trying to understand more advanced machine learning concept along with mathematics behind its.</p>

          <p>I'm mostly familar and working with Deep learning in the field Computer vision such as deep generative model, however I always keep exploring fun stuffs in machine learning that I have not discovered yet!! </p>
        </div>

      </div>
      

    </div>

    <div>


    </div>
  </div>

</template>




<script>


export default{

  name : 'home',

}
</script>


<style scoped>

.title {
  
  font-weight : bold;
  font-size : 50px;
  color : var(--green);
  margin-bottom :25px;
}

.rounded-circle{
border:none;
border-radius:50%;

}

.highlight-red{

  display : inline;
  color: var(--red)

}


.highlight-pink{

  display : inline;
  color: var(--pink)

}

.col-img{
display : flex;
  align-items: center;
}

</style>

