<template>
  <div>
    <h1>{{ msg }}</h1>
    <hr style="width: 100px">
    <p>
      Chinese name usually carries a lot more than only a name.
    </p>
    <p> Normally it has wills and wishes from parents and a person's personality.</p>
    <p> Guess nobody wants to have a name with bad or ridiculous meanings in Chinese culture.</p>
    <p>
      In order to get your satisfied name, I need to know a little more details about you.
    </p>
    <hr style="width: 100px">
    <div>
      <ul>
        <li>Your gender</li>
        <li>The meaning you want your name carries</li>
        <li>Your country</li>
        <li>Your real name</li>
        <li>The meaning of your real name</li>
        <li>Your birth month</li>
        <li>Your birth time (optional)</li>
        <li>The weather on the day you borned (optional)</li>
      </ul>
    </div>
    <h3>Please send above information to cocoacube@qq.com.</h3>
    <h3>Price: 10 USD</h3>
  </div>
</template>

<script>
  export default {
    name: 'HelloChineseName',
    props: {
      msg: String
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3 {
    margin: 40px 0 0;
  }
  
  ul {
    list-style-type: circle;
    padding: 0;
  }
  
  li {
    /* display: inline-block; */
    /* margin: 0 10px; */
  }
  
  a {
    color: #42b983;
  }
</style>
