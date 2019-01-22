<template>
  <div class="hello hero is-fullheight-with-navbar ">
    <div class="hero-body">
      <div class="container">
        <img src="../assets/logo.png" >
        <p class='title has-text-white'>{{ msg }}</p>
        <p class="subtitle has-text-white">This page is a mixture of Vuejs and Bulma, it has very little purpose other than to test my skills with api calls and intergrating a CSS framework with a Javascript framework. Below are my linkedin, github, and a way to return to my protfolio.</p>
<div class="columns is-size-3 has-text-white">
  <div class="column "><a href="https://www.linkedin.com/in/forcharles/"><i class="fab fa-linkedin-in"></i></a></div>
  <div class="column"><a href="https://github.com/IamCharlesM"><i class="fab fa-github"></i></a></div>
  <div class="column"><a href="https://charlesis.me"><i class="fas fa-desktop"></i></a></div>
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

a:visited {
  color: white;
}

a:hover {
  color: #c9d6df
}
</style>
