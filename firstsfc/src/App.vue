<template>
  <h1>My Healthy Food Choices!!!</h1>
  <FoodItem />
  <FoodItem2 />
</template>

<script>
import FoodItem from './components/FoodItem.vue'
import FoodItem2 from './components/FoodItem2.vue'

export default {
  components: {
    FoodItem,
    FoodItem2
  }
}
</script>

<style>
h1 {
  margin-bottom: 20px;
}
</style>
