<template>
<div class="form p-5">
  <ContactUsInput inputLabel="Nome"/>
  <ContactUsInput inputLabel="Sobrenome"/>
  <ContactUsInput inputLabel="E-Mail"/>
  <ContactUsInput inputLabel="CPF"/>
  <ContactUsInput inputLabel="Nº/Pedido"/>
  <ContactUsSelect/>
  <button class="btn btn-outline-dark mt-5">ENVIAR</button>
</div>
</template>

<script>
import ContactUsInput from './ContactUsInput.vue'
import ContactUsSelect from './ContactUsSelect.vue'

export default {
  name: 'ContactUs',
  components: {
    ContactUsInput,
    ContactUsSelect
  },
  props: {
    mensagem: String
  }
}
</script>

<style scoped>

</style>
