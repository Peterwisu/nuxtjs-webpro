<template>

  <div>
    <div class='container mt-5 '>
      
      
      <div class='row'>

        <div class='col-md-8'>

          
        <p class='title'> Wish Suharitdamrong </p>     


          <h4> I am  a computer scientist specialized in the area of Artificial Intelligence (AI). My main interest in AI are <p class="highlight">Machine learning (Deep learning)</p>, <p class="highlight">Computer Vision</p> and <p class="highlight">Evolutionary Computation</p>.</h4>

          <p>I am  currently studying my final year undergradute in BSc computer science at University of Surrey.</p> 

        </div>

        <div class='col-md-4 col-img'>

          <!----<img :src='image' class="img-fluid rounded">--->


          <!---<b-img :src='image' clalss='img' fluid-grow rounded="circle"></b-img>--->
          <img src='~/assets/img/profile.jpg' class='img-fluid rounded-circle' >

          

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
}

.rounded-circle{
border:none;
border-radius:50%;

}

.highlight{

  display : inline;
  color: var(--red)

}

.col-img{
display : flex;
  align-items: center;
}

</style>

