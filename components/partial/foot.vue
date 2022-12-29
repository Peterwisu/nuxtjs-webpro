<template>




  <div> 
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <br> 
    <footer class="fixed-bottom">

      <div class="container-fluid" id="border">

        <div class="row justify-content-between">

          <div class='col-7'>
            <p class='footer'>{{fileName()}}</p>
          </div>

          <div class='col-5'>


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

                <a href="https://www.linkedin.com/in/wish-suharitdamrong-534948229/"class='footer'>
                  <img class="img-fluid icon" src="~/assets/img/linkedin-icon.png" /> 
                  Linkedin
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
  </div>


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


      path : this.$route.path,


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

    },
   

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

.footer:hover {

 
 text-decoration : none;

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
