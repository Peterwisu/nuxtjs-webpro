<template>
  <div>
    <div class='container'> 
      <div class="row">
      
        
        {{visible}}
        <div v-for="item in items" class='col-md-4'> 
          <b-card
            v-bind:title="item.name"
            title-tag="h6"
            img-src=""
            img-alt="NoImage"
            img-top
            tag="article"
            body-class="card-body"
            style="max-width: 20rem; border-color : var(--border); border-width: 2px ;background-color : var(--hover);"
            class="mb-2">
            <b-card-text>
              <p class="content">{{item.content}}</p>
            </b-card-text>
            <b-button size='sm'v-bind:href="item.link.github" active-class="card-body" variant="primary">
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

export default{

  props: {

    items :  Array ,

  },

  data() {
    
    return {
    buttonText : 'Show more',
    }
  },

  methods : {

    showMore:()=>{
        
      console.log('asdasd')

    }


  }


}

</script>


<style scoped>


.content{

  font-size: 12px;
}
h6 {

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
