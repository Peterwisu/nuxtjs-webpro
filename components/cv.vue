<template>

  <div> 

    <div class='container'>

      <div class="row justify-content-between mx-5 my-5">

        
        <p class='title'>Curriculum vitae </p>


        <a href="~/assets/files/cv.pdf" download='cv.pdf'>Download CV</a>
        


      </div>

      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>General Information</h3>
        </div>
        <div class="card-body"> 
          
          <p class="info"><b>Full Name :</b>  Wish Suharitdamrong</p>
          <p class="info"><b>Languages  :</b>   English (Fluent), Thai (Native)</p>
        </div>
      </div>

      
      <!---------- Education ------->
      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>Education</h3>
        </div>
        <div class="card-body"> 
          <div class='row justify-content-center'>
            <div class="col-md-6">
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>BSc Computer Science</h5>
              <p>University of Surrey, Guildford, United Kingdom</p>
            </div>
          </div>
          <hr>
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>International Foundation Year</h5>
              <p>University of Surrey, Guidlford, United Kingdom</p>
            </div>
          </div>
          <hr> 
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>IGCSE Examination</h5>
              <p>Home School (self studies), Bangkok, Thailand</p>
            </div>
          </div>
          <hr>
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>Middle School</h5>
              <p>Genesis Global School, Noida, India</p>
            </div>
          </div>
          <hr> 
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>Primary to Middle School</h5>
              <p>Saint Joseph North Point, Darjeeling, India</p>
            </div>
          </div>
          <hr>
          <div class='row justify-content-center'>
            <div class="col-md-6">
            
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>Primary School</h5>
              <p>Saint Garbriel College, Bangkok, Thailand</p>
            </div>
          </div>
        </div>
      </div>

      <!--------- End Education ------->

      <!--------- Experience -------> 
      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>Experience</h3>
        </div>
        <div class="card-body"> 
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>June - August 2022</p>
            </div>
            <div class="col-md-6">
              <h5>Research Assistance</h5>
              <p>University of Surrey, Guildford, United Kingdom</p>
            </div>
          </div>
    
        </div>
      </div>
      <!--------- Experience ------->


      <!--------- Honors and Awards -------> 
      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>Honors and Awards</h3>
        </div>
        <div class="card-body"> 
          <div class='row justify-content-center'>
            <div class="col-md-6">
              
             <p class='year'>2020-Present</p>
            </div>
            <div class="col-md-6">
              <h5>Cambridge Outstadning Awards</h5>
              <p>Highest marks in IGCSE computer science in Thailand</p>
            </div>
          </div> 
        </div>
      </div>
      <!--------- Experience ------->
      <!----------Academic interest------------>
      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>Academic Interests</h3>
        </div>
        <div class="card-body">
          <div class="row justify-content-around"> 
            <div class='col-md-6'>
              <h5> Machine Learning & Computer Vision</h5>
              <ul>
                <li>Supervised Learning</li>
                <li>Unsupervised Learning</li>
                <li>Deep Learning</li>
                <li>Generative Model (Image & Video generation)</li> 
              </ul>
            </div>
            <div class='col-md-6'>

              <h5> Evolutionary Computation </h5>
              <ul>
                <li>Genetic Algorithms</li>
                <li>Swarm Intelligence</li>
              </ul>
            </div>
          </div>
        </div>
      </div>



      <div class="card mx-5 my-5">
        <div class="card-header">
          <h3>Skills</h3>
        </div>
        <div class="card-body">
          <div class="row justify-content-around"> 
            <div class='col-md-6'>
              <h5> Programming Language</h5>
              <ul>
                <li>C/C++</li>
                <li>Java</li>
                <li>Javascripts</li>
                <li>Python (mainly)</li> 
                <li>R </li>
                <li>Ruby</li>
                <li>PHP</li>
              </ul>
            </div>
            <div class='col-md-6'>
              <h5> ML libraries &  frameworks</h5>
              <ul>
                <li>Pytorch (mainly)</li>
                <li>Tensorflow</li>
                <li>Keras</li>
                <li>Scikit-Learn</li>
              </ul>
            </div>
      
            <div class='col-md-6'>
              <h5>Operating System</h5>
              <ul>
                <li>MacOS</li>
                <li>Windows</li>
                <li>Linux (mainly)</li>
              </ul>
            </div>


            <div class='col-md-6'> 
              <h5> Tools & Others</h5>
              <ul>
                <li>HTCondor</li>
                <li>Latex</li>
              </ul>
            </div>

          </div>

        </div>
      </div>






 
      

    </div>
  </div>




</template>




<script>


export default {
  
  name : 'cv',

 
}

</script>



<style scoped>

.title {

  font-weight: bold;
  font-size : 50px;
  color: var(--green);
}

.card-header{

  background-color: var(--hover);
  color : var(--red);
}

.card-body{

  background-color : var(--hover);
}

div.col-md-6 h3, div.col-md-6 h5{
  
  color : var(--yellow)
}

a{


  color : var(--pink);
  font-weight :  bold;
  display : flex;
  align-items: center;

}

.card {

  border-color: var(--gray);
  border: solid
}






</style>
