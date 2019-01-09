<template>
  <div class="hello">
    <b-alert show>{{ msg }}</b-alert>
  </div>
</template>

<script>
  export default {
    name: 'Index',
    data() {
      return {
        msg: 'Let`s start'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
