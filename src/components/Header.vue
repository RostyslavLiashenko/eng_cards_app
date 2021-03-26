<template>
  <header class="header">
    <div class="left_trap"></div>
      <a href="#" class="header_home">
        <img src="../assets/dog1.jpg" alt="Dog logo" class="header_logo">
      </a>
    <div class="right_trap"></div>
  </header>
</template>

<script>
export default {
name: "Header"
}
</script>

<style scoped>
.header {
  max-width: 1440px;
  height: 40px;
  margin: 0 auto;
}
.header_home {
  display: inline-block;
  padding: 8px 0 0 140px;
}
.header_logo {
  max-width: 85px;
}
.left_trap {
  max-width: 120px;
  width: 100%;
  border-top: 40px solid #cab87f;
  border-right: 40px solid transparent;
  position: absolute;
}
.right_trap {
  display: inline-block;
  max-width: 1130px;
  width: 100%;
  border-top: 40px solid #cab87f;
  border-left: 35px solid transparent;
  position: absolute;
}
</style>