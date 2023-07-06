<template>
<div class="input-group input-group-sm mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text" id="inputGroup-sizing-sm">{{inputLabel}}</span>
  </div>
  <input type="text" class="form-control" aria-label="Small" aria-describedby="inputGroup-sizing-sm">
</div>
</template>

<script>
export default {
    name: 'ContactUsInput',
    props: {
        inputLabel: String
    }
}
</script>

<style>
</style>
