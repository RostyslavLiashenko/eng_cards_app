<template>
  <div class="container_start_page">
    <auth class="auth"></auth>
  </div>
</template>

<script>
import auth from "../components/auth";

export default {
  name: 'StartPage',
  components: {
    auth,
  }
}
</script>

<style scoped>
  .container_start_page {
    display: flex;
    padding: 0 40px;
    justify-content: space-around;
  }
  .auth {
    align-self: center;
  }
</style>