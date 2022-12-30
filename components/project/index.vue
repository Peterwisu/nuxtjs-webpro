<template>

  <div>

    <div class='container'>

      <div class='row mx-5 my-5'>

        <div class='col-12'>
          <p class='title'>My Project</p>
        </div> 

        <div class='col-12 my-5'>
          <h3 class="section">University Assignments</h3>

          <list/> 


        </div>

        <div class='col-12 my-5'>

          <h3 class="section">My Thesis</h3>
        </div>

        <div class='col-12 my-5'>

          <h3 class="section">My own projects</h3>
        </div>



      </div>

    </div>

  </div>


</template>


<script>


import list from './list.vue'

export default{

  name : "index",

  components : {

    list
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


}


</style>
