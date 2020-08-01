<template>
  <div>
    <button @click="login"> Login/Register </button>
  </div>
</template>

<script>
    export default {
        name: "login",
      methods: {
          login: function () {
            this.$auth.loginWith('auth0')
          }
      }
    }
</script>

<style scoped>

</style>
