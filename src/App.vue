<template>
<ContactUsTitle tituloForm="Em que podemos ajudar?"/>
<ContactUs/>
</template>

<script>
import ContactUs from './components/ContactUs.vue'
import ContactUsTitle from './components/ContactUsTitle.vue'

export default {
  name: 'App',
  components: {
    ContactUs,
    ContactUsTitle
  }
}
</script>

<style scoped>
</style>
