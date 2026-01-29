<template>
  <div class="Mango">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Mango, Apple, Guava, Carrots, and Broccoli',
      message: 'I like eating fruits and vegetables'
    }
  }
}
</script>

<style>
.Mango {
  border: dashed black 1px;
  display: inline-block;
  margin: 10px;
  padding: 10px;
  background-color: lightgreen;
}
</style>
