<template>
  <div class="comp">
    <img :src="image" alt="">
    <p><slot></slot></p>
  </div>
</template>

<script>
export default {
  props: {
    image: {
      type: [String , Number] ,
      required: true 
    }
  }
}
</script>

<style>
.comp {
  display: block;
}

.comp p {
  color: #000;
  font-family: Arial;
  font-size: 17px;
  font-style: normal;
  font-weight: 400;
  line-height: 25.2px; /* 148.235% */
}
</style>
