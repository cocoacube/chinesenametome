<template>
  <div id="app">
    <div>
      <img alt="logo" src="./assets/confucius.jpg" style="width: 100%">
    </div>
    <HelloWorld msg="Hello, whom wants a proper Chinese name!" />
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'
  
  
  export default {
    name: 'app',
    metaInfo: {
      // Children can override the title.
      title: 'Chinese name to me | I will help you to get a proper Chinese name',
      // Result: My Page Title ← My Site
      // If a child changes the title to "My Other Page Title",
      // it will become: My Other Page Title ← My Site
      titleTemplate: '%s ← My Site',
      // Define meta tags here.
      meta: [{
          name: 'viewport',
          content: 'width=device-width, initial-scale=1'
        },
        {
          name: 'description',
          content: 'chinesenameto.me is a site helping people who wants to have a proper Chinese name. Name is a very important symbol in China. It shows person\'s personality, wills and dreams. A Chinese name is also reveals a person\'s education and growing environment. My mission is to help people who need a real Chinese name, which is suitable for them.'
        }
      ]
    },
    components: {
      HelloWorld
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /* margin-top: 60px; */
    margin-bottom: 50px;
  }
</style>
