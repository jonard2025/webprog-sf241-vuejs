<template>
  <div>
    <h1>My Healthy Food Choices!!!</h1>
    <PersonalProfile />
    <FoodItem />
    <FoodItem2 />
  </div>
</template>

<script>
import PersonalProfile from './components/PersonalProfile.vue'
import FoodItem from './components/FoodItem.vue'
import FoodItem2 from './components/FoodItem2.vue'

export default {
  name: 'App',
  components: {
    PersonalProfile,
    FoodItem,
    FoodItem2
  }
}
</script>

<style>
h1 {
  margin-bottom: 20px;
  text-align: center;
  color: #2c7a7b;
  font-family: Arial, Helvetica, sans-serif;
}
</style>
