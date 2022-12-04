<template>
<div>
    <ul>
        <li v-for="(product, index) in products" :key="index" v-text="product">{{loadProducts}}</li>
    </ul>
</div>
</template>

<script>
import productMixin from '../mixin/productMixin.js'
export default {
   mixins: [productMixin]
};
</script>

<style scoped>

</style>
