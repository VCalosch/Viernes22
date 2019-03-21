<template>
  <div id="app">
    <div class="columns">
    <SideBar/>
      <div class="column">
        <NavBar/>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SideBar from './components/SideBar.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    SideBar
  }
}
</script>

<style>
@import './assets/css/venus.css';

</style>
