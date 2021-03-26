<template>
  <Header></Header>
  <StartPage></StartPage>
</template>

<script>
import Header from "./components/Header";
import StartPage from "./pages/StartPage";

export default {
  name: 'App',
  components: {
    Header,
    StartPage,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

body {
  margin: 0;
  overflow: hidden;
}
</style>
