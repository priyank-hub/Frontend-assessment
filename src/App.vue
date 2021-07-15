<template>
  <div id="app">
    <div class="container-fluid">
      <div class="row justify-content-center mt-6">
        <div class="col-3 col-xs-4 col-sm-2 col-md-2 p-0">
          <side-bar />
        </div>
        <div class="col-9 p-0">
          <HelloWorld msg="Welcome to Your Vue.js App"/>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SideBar from './components/SideBar'

export default {
  name: 'App',
  components: {
    HelloWorld,
    SideBar,
  }
}
</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400&display=swap');

  #app {
    background-color: #1d2c96;
    font-family: 'Raleway';
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>


