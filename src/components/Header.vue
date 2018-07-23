<template>
<div class="container">
  <div class="header-container">
    <div class="title">
      <span>:)</span>
    </div>

    <ul class="menu">
      <li><a href="#">home</a></li>
      <li><a href="#">about</a></li>
      <li><a href="#">contact</a></li>
    </ul>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
.header-container {
  padding: 20px 0 20px 0;
  height: 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  .title {
    width: 40%;
  }

  .menu {
    list-style: none;
    display: flex;
    justify-content: center;
    
    li {
      min-width: 80px;
    }
  }
}
</style>
