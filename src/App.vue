<template>
  <div id="app">
      <SongList/>
      <PlayList/>
  </div>
</template>

<script>
import SongList from './components/SongList.vue'
import PlayList from './components/PlayList.vue'

export default {
  name: "App",
  components: {
    SongList,
    PlayList
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: grid;
  grid-template-columns: 1fr 1fr;
}
</style>
