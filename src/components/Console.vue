<template>
<div class="container">
  <div class="console-container">
    <div class="console-output">
      <h2>$ Wanna talk?_</h2>

      <ul>
        <li>
          StackOverflow: <a target="_blank" href="https://stackoverflow.com/users/2360791/eduardo-aguad">https://stackoverflow.com/users/2360791/eduardo-aguad</a>
        </li>
        <li>
          LinkedIn: <a target="_blank" href="https://www.linkedin.com/in/eduardo-aguad-076710114">https://www.linkedin.com/in/eduardo-aguad-076710114</a>
        </li>
        <li>
          Email: <a href="mailto:eduaguad@gmail.com">eduaguad@gmail.com</a>
        </li>
      </ul>
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
