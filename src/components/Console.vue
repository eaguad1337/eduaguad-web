<template>
<div class="container">
  <div class="console-container">
    <div class="console-output">
      <p>Wanna talk? eduaguad[at]gmail[dot]com</p>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'Console',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

.console-container {
  padding: 30px;
  border: 1px dashed;


  ul {
    line-height: 16px;
    list-style: none;

    li.item {
      padding-left: 15px;
    }
  }

  .console-header {
    font-weight: 600;

  }

  .console-output {
    line-height: 17px;
    font-size: 13px;
  }
}
</style>
