<template>
  <div id="app">
    <div class="click-closed"></div>
    <SearchTab />
    <NavBar />
    <HomePage/>
  </div>
</template>

<script>
import HomePage from './components/home/homePage.vue';
import SearchTab from './components/shared/searchTab.vue';
import NavBar from './components/shared/navBar.vue';

export default {
  name: 'app',
  components: {
    HomePage,
    SearchTab,
    NavBar,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
