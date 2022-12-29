<template>

  
  
  <footer class="fixed-bottom">
    <div class="container-fluid" id="border">

      <div class="row justify-content-between">
    
        <div class='col-8'>
          <p class='footer'>{{fileName()}}</p>
        </div>

        <div class='col-4'>

          
          <div class='row justify-content-end'>


            <div class='col d-flex justify-content-end'>

              <p class='footer'>UTF-8</p>

            </div>

            <div class='col d-flex justify-content-end'>

              <p class='footer'>HTML</p>

            </div>
            <div class='col d-flex justify-content-end'>

              <a href="https://github.com/Peterwisu"class='footer'>
                <img class="img-fluid icon" src="~/assets/icons/github-mark-white.svg" /> 
                Gtihub
              </a>

            </div>
            <div class='col d-flex justify-content-end'>

              <p class='footer'>index.html</p>
            </div>

          </div>
        </div>
      </div>      
    </div>
  </footer>


</template>


<script>

import githubicon from "~/assets/icons/github-mark-white.svg"

export default{

  name : 'foot',

  data(){

    return {

      githubicon
    } 
  },

  data() {
    return{


      path : this.$route.path

    }
  },

  methods: {

    fileName(){

      let name = ''
      if(this.path === '/'){

        name = 'index.html'

      }else {

        name =  this.path.split('/')[1]  + '.html'

      }

      return name

    }

  }

}

</script>



<style scoped>

footer {

  background-color : var(--bg2);


}

.footer {
  color : var(--font);
  border-width: 1px;
  border-color: var(--border);
  
  margin : 2px;
  padding : 5px;

}

.col {

  border :9px; 

  border-color : var(--border);

}

.icon{

  width:22px;
  height:22px;

}

#border{

  border-top : 2px solid ;
  border-color : var(--border);
    
}



</style>
