<template>
  <div class="Apple">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Apple, Guava, Carrots, and Broccoli',
      message: 'I like eating fruits and vegetables'
    }
  }
}
</script>

<style>
.Apple {
  border: dashed black 1px;
  display: inline-block;
  margin: 10px;
  padding: 10px;
  background-color: rgb(25, 240, 25);
}
</style>
