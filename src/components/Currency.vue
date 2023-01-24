<template>
  {{dollar(amt)}}
</template>

<script>
export default {
  name: 'Currency',
  props: ['amt'],
  methods: {
    dollar(value) {
      return '$' + Number.parseFloat(value).toFixed(2);
    }
  }
}
</script>

<style scoped>

</style>