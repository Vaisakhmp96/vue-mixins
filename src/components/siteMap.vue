<template>
    <div>
        <h1>{{title}}</h1>
      <ul>
        <li>Home</li>
        <li>About</li>
        <li>Products
            <ul>
                <li v-for="(product, index) in products" :key="index" v-text="product">{{loadProducts}}</li>
            </ul>
        </li>
      </ul>
    </div>
</template>

<script>
    import productMixin from '../mixin/productMixin.js'
export default {
   mixins: [productMixin],
   data() {
      return {
        title: 'Sitemap'
      }
   }
};
    
</script>

<style scoped>

</style>