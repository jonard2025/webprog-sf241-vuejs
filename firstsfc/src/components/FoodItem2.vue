  <div class="Apple"></div>>
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>

<script>
export default {
  data() {
    return {
      name: 'Apple, Guava, Carrots and Brocolli',
      message: 'I like eating Fruits and Vegestables'
    }
  }
};
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