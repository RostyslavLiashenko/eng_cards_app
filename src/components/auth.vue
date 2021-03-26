<template>
    <div>
      <h2>Registration</h2>
      <p>Username</p>
      <input type="text" placeholder="John Cena">
      <p>Email</p>
      <input type="email" placeholder="johncena@gmail.com">
      <p>Password</p>
      <input type="password" placeholder="password">
      <RegBtn></RegBtn>
      <AuthBtn class="auth_btn"></AuthBtn>
    </div>
</template>

<script>
import RegBtn from "./RegBtn";
import AuthBtn from "./AuthBtn";
export default {
  name: "auth",
  components: {
    RegBtn,
    AuthBtn
  }
}
</script>

<style scoped>
  div {
    font-family: 'Poppins', sans-serif;
  }
  h2 {
    font-size: 1.3em;
  }
  p {
    margin: 20px 0 5px 0;
    font-size: 1.05rem;
  }
  input {
    font-family: 'Roboto', sans-serif;
    color: #333;
    font-size: .95rem;
    padding: 1.05em 3.5em 1.05em 1.1em;
    border-radius: 0.3rem;
    background-color: #F8F8F8;
    border: 1px solid #E5E0E0;
    width: 90%;
    display: block;
    border-bottom: 0.3rem solid transparent;
    transition: all 0.3s;
  }
  input:last-of-type {
    margin-bottom: 2.5em;
  }
  .auth_btn {
    margin-left: 1em;
  }
</style>