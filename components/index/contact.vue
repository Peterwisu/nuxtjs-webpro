<template>

  <div class='container'>
    <div class='row  mx-5 mt-5'>
      <p class='title'>Contact Me</p>
    </div>
    <div class="card my-2 mx-5">
      <div class="card-header">
        <h3>Contact Information</h3>
      </div>
      <div class="card-body"> 
        <div class="row justify-content-around"> 
          <div class='col-md-6'>
            <h5 class='type'> Email Address</h5>
            <p class=""><b>Personal Email:</b>  peterwisu@gmail.com</p>
            <p class=""><b>University Email:</b>   ws00372@surrey.ac.uk</p>
          </div>
          <div class='col-md-6'>
            <h5 class="type"> Social Media</h5>
            <p class=""><b>Linkedin :</b>   Wish Suharitdamrong</p>
            <p class=""><b>Instagram:</b>   Mysoulmywish</p>
          </div>
        </div>
      </div>
    </div>
  </div>


</template>




<script>


export default{
  
  name : "contact",
}


</script>





<style scoped>


.title {


  color : var(--green);
  font-size : 50px;
  font-weight : bold;

}

.type{
  
  
    font-weight :  bold;
}


.card-header{

  background-color: var(--hover);
  color : var(--red);
}

.card-body{

  background-color : var(--hover);
}

b{

  color: var(--yellow)

}






</style>
