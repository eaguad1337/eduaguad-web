<template>
<div class="container">
  <div class="console-container">
    <div class="console-output">
      <p>Welcome to my humble webpage ;)</p>
      <p>I'm Eduardo Aguad and I live in Santiago, Chile. Doing backend is my favorite thing to do but I worked in some cool apps with javascript and vue.js framework.</p>
      <p>Also, I enjoy working with linux servers (specially debian-based). Some of the services I can configure are nginx, mysql, php-fpm, ssh, etc. Even this is not my "primary skill", I know to look when I need to add a feature or search for an error.</p>
      <p>---------------------------------------</p>
      <p>I am self-taught and consider myself a very lucky because I have worked with amazing people.</p>
      <p>Programing Skills:</p>
      <ul>
          <li>{</li>
          <li class="item">"php":"~7.0",</li>
          <li class="item">"mysql":"~5.7",</li>
          <li class="item">"javascript":"es6"</li>
          <li>}</li>
      </ul>
      <p>Technologies learned</p>
      <ul>
          <li>{</li>
          <li class="item">"laravel/framework":"~5.6",</li>
          <li class="item">"vue":"~2.0"</li>
          <li>}</li>
      </ul>
      <p>Other technologies I know:</p>
      <ul>
        <li>Salesforce – Visualforce Pages with Vue.js and HTML connected to Apex Controllers.</li>
        <li>Hybrid Mobile Apps with Apache Cordova</li>
      </ul>
      <br>
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
