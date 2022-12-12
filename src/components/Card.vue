<template>
  <div class="card">
    <img :src="imageUrl" alt="Avatar" style="width:100%">
    <div class="card-container">
      <h4>{{ name }}</h4> 
      <p>{{ occupation }}</p> 
    </div>
  </div>
</template>

<script>
export default {
  props: {
    name: '',
    occupation: '',
    imageUrl: ''
  }
}
</script>