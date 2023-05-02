
<script>
export default{
  name: 'ProductList'
}
</script>

<template> 
   <div class="cont">
    <div class="products">
          <span>Prodotto</span>
    </div>
    <div class="products">
          <span>Prodotto</span>
    </div>
    <div class="products">
          <span>Prodotto</span>
    </div>

   </div>
</template>

<style lang="scss" scoped>

.cont{
  display: flex;
  flex-wrap: wrap;
  .products{
    flex-basis: calc(100% / 6);
    border: 1px solid white;
    span{
      background-color:  white;
    }
  }
}
</style>
