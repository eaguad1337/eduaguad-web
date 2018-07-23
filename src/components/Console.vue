<template>
<div class="container">
  <div class="console-container">
    <div class="console-output">
      <p>Welcome to my humble webpage ;)</p>
      <p>I am a web developer and I am always learning something new. Backend is my favorite thing to do but I did some cool apps with javascript and vue.js framework.</p>
      <p>Also, I enjoy working with linux servers (specially debian-based). Some of the services I can configure are nginx, mysql, php-fpm, ssh, etc. Even this is not my "primary skill", I know to look when I need to add a feature or search for an error.</p>
      <p>I like cats, I have 3 cats called Emily, Anastasia and Orange–Cat and they love to prr on me. Bicycle and running is my hobby. I'm a little lazy but I do my best :)</p>
      <p>---------------------------------------------</p>
      <p>Almost everything I know was self-taught. I'm very lucky because I have worked with amazing people!</p>
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
      <br>
      <p>Do you wanna talk? eduaguad[at]gmail[dot]com</p>
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
