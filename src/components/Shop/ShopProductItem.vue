<template>
  <div class="w-25 p-3 product-container d-flex flex-column">
    <div class="d-flex flex-row justify-content-center">
     <img style ="height:150px" v-bind:src="product.img"/>
    </div>
    <div>
      <h3>{{product.title}}</h3>
      <hr>
    </div>
    <div>
      <p>{{product.description}}</p>
    </div>
    <div>
      <span>{{product.price}}</span>
    </div>
  </div>
</template>

<script>

// import {eventBus} from '../../main.js'

export default {  
 
  props: ['product'] // on conserve le nom 'product'
  // methods:{
  //   addProductToCart(){
  //     eventBus.addProductToCart({ ...this.product })
  //   }
  // }
}
</script>

<style>
.product-container{
  height:400px;
}
p{
  font-size: 12px;
}
</style>
