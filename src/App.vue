<template>
  <div id="app">
    <link rel="stylesheet" href="//cdn.materialdesignicons.com/2.5.94/css/materialdesignicons.min.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
    <router-view></router-view>
    <div class="hero-foot">
    <nav class="tabs is-boxed is-fullwidth">
      <div class="container">
        <ul>
          <li><a><router-link :to="{ name: 'Hello' }">Home</router-link></a></li>
          <li><a><router-link to="/about">About Cryptocurrency</router-link></a></li>
          <li><a><router-link to="/coins/ethereum">Ethereum</router-link></a></li>
          <li><a><router-link to="/coins/bitcoin-cash">Bitcoin Cash</router-link></a></li>
          <li><a><router-link to="/coins/ripple">Ripple</router-link></a></li>
          <li><a><router-link to="/coins/eos">EOS</router-link></a></li>
          <li><a><router-link to="/coins/litecoin">Litecoin</router-link></a></li>
        </ul>
      </div>
    </nav>
  </div>

  </div>
</template>

<script>
  export default {
    name: 'App'
  }

</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    margin-top: 60px;
    background-color: #a2aab1;
    margin: 0 auto;
    height: 100% !important;
  }

  router-view {
    margin: 0 auto;
    height: 100% !important;
  }

  img {
    max-height: 300px;
  }

</style>
