<template>
<div class="form p-5">
  <ContactUsInput inputLabel="Nome"/>
  <ContactUsInput inputLabel="Sobrenome"/>
  <ContactUsInput inputLabel="E-Mail"/>
  <ContactUsInput inputLabel="CPF"/>
  <ContactUsInput inputLabel="Nº/Pedido"/>
</div>
</template>

<script>
import ContactUsInput from './ContactUsInput.vue'

export default {
  name: 'ContactUs',
  components: {
    ContactUsInput
  },
  props: {
    mensagem: String
  }
}
</script>

<style scoped>

</style>
