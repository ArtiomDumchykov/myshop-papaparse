<template>
  <div id="app">
    <h1>My SHOP</h1>
    <ProductList />
    <ReviewsComponent/>
    <FooterComponent />
  </div>
</template>

<script>
import ProductList from './components/ProductList.vue';
import FooterComponent from './components/FooterComponent.vue';
import ReviewsComponent from './components/ReviewsComponent.vue'

export default {
  components: {
    ProductList,
    FooterComponent,
    ReviewsComponent,

  },
};
</script>