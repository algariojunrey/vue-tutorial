<script setup>
import PageTitle from '../components/PageTitle.vue'
import Card from '../components/Card.vue'
</script>

<template>
  <div class="container">
    <page-title title="Home"></page-title>
    <card 
      name="Junrey Algario" 
      occupation="Software Engineer"
      :image-url="avatar"
    ></card>
  </div>
</template>

<script>
import avatar from '../assets/images/img_avatar.png'

export default {
  // components: [title, Card]
}
</script>