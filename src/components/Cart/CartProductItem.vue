<template>
  <div class="d-flex flex-row justify-content-between p-2">
    <span style="width:130px;"> {{ item.title }} </span>
    <span><strong> {{ item.price }} € </strong></span>
  </div>
</template>

<script>

export default {  
  props:['item']
  }

</script>

<style>

</style>
