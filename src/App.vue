<template>
  <div id="app">
    <HeaderList/>
    <SideBarList/>
  </div>
</template>

<script>
import HeaderList from "./components/HeaderList";
import SideBarList from "./components/SideBarList";

export default {
  name: "App",
  components: {
    HeaderList,
    SideBarList
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
