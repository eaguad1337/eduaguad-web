<template>
  <div id="app">
    <Header></Header>
    <Console />
  </div>
</template>

<script>
import Console from './components/Console.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    Console, Header
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
}

#app {
  padding: 10px;
  min-height: 100vh;
  position: relative;
  font-family: 'Courier new';
  color: #00FF00;
  background-color: black;

  a:link, a:visited {
    color: inherit;
  }

  .container {
    max-width: 920px;
    margin: 0 auto;
  }

  input[type=text] {
    border: 1px solid #00FF00;
    padding: 5px;
    background-color: black;
    color: #00FF00;
    width: 100%;
  }
  input[type=text]:focus, input[type=text]:active {
    border: 1px solid #00FF00;
  }
}
</style>
