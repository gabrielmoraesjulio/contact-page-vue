<template>
<h1 class="mb-5">Em que podemos ajudar?</h1>
<ContactUs/>
</template>

<script>
import ContactUs from './components/ContactUs.vue'

export default {
  name: 'App',
  components: {
    ContactUs
  }
}
</script>

<style scoped>
body {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-image: linear-gradient(0deg, rgba(32,0,54,1) 0%, rgba(102,0,255,1) 100%);
    background-attachment: fixed;
    color: white;
}
</style>
