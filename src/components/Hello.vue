<template>
  <div class="hello hero is-fullheight-with-navbar ">
    <div class="hero-body">
      <div class="container">
        <img src="../assets/logo.png" >
        <p class='title has-text-white'>{{ msg }}</p>
        <p class="subtitle has-text-white">This page is a mixture of Vuejs and Bulma, it has very little purpose other than to test my skills with api calls and intergrating a CSS framework with a Javascript framework. Below are my linkedin, github, and a way to return to my protfolio.</p>
<div class="columns is-size-3 has-text-white">
  <div class="column "><i class="fab fa-linkedin-in"></i></div>
  <div class="column"><i class="fab fa-github"></i></div>
  <div class="column"><i class="fas fa-desktop"></i></div>
</div>

      </div>
    </div>

  </div>
</template>

<script>
  export default {
    name: 'Hello',
    data() {
      return {
        msg: 'Welcome to V-Crypt'
      }
    }
  }

</script>

<style scoped>
.hello {
  height: 100% !important;
  margin: 0 auto;
}
</style>
