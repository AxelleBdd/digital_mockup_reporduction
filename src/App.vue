<template>
  <div class="app">
    <Header />
    <SearchBar />
    <mainDisplay />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import SearchBar from './components/SearchBar.vue';
import MainDisplay from './components/mainDisplay.vue';

export default {
  components: {
    Header,
    SearchBar,
    MainDisplay
  }
};
</script>

<style>
body {
  margin: 0;
  font-family: sans-serif;
}

.app {
  padding: 1rem;
}
</style>
