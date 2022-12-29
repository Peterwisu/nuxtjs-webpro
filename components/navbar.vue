<template>

  <div>




    <ul class="nav nav-tabs nav-fill">
      <li class="nav-item">
        <a v-bind:class=" {active: $route.path ===  '/'} " class="nav-link" href="/">Home</a>
      </li>
      <li class="nav-item">
        <a  v-bind:class="{active: $route.path === '/project'}" id="project" class="nav-link" href="/project">Project</a>
      </li>
      <li class="nav-item">
        <a v-bind:class="{active: $route.path === '/cv'}" class="nav-link " href="/cv">CV</a>
      </li>

      <li class="nav-item">
        <a  v-bind:class="{active: $route.path === '/contact'}" class="nav-link" href="/contact">Contact</a>
      </li>
    </ul>

  </div>

</template>


<script>


  export default{
   name : "navbar" ,


  }

</script>



<style>

.nav-tabs {


  border-bottom : none;
}

.nav-tabs a.nav-link.active{
  
 background-color: var(--bg); 
 color : var(--font); 
 font-weight : bold;
 border-bottom :none;
 border-radius: 0px;
 border-right-color :var(--border);
 border-left-width : 3px;
 border-left-color : var(--blue);  

}


.nav-tabs a.nav-link.active:hover{
  
 border-left-color : var(--blue);  
}


.nav-tabs a.nav-link{
  
 background-color: var(--bg2); 
 color : var(--font); 
 font-weight : bold;
 border-color : var(--border);
 border-radius : 0px;
 border-top : none;
}


.nav-tabs a.nav-link:hover{
  
 border-color : var(--border);
 border-radius : 0px;
 border-top : none;
}





</style>

