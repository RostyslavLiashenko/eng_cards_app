<template>
  <button>Register</button>
</template>

<script>
export default {
name: "RegBtn"
}
</script>

<style scoped>
  button {
    background: #cab87f;
    background: linear-gradient(0deg, rgba(190,173,120,1) 27%, rgba(195,177,122,1) 59%, rgba(202,184,127,1) 100%);
    outline: none;
    color: #fff;
    border-radius: 0.3rem;
    border: none;
    width: 220px;
    height: 50px;
    font-family: 'Poppins', sans-serif;
    font-size: 1.06em;
    cursor: pointer;
    transition: box-shadow .4s, transform .1s;
  }
  button:hover {
    box-shadow: 6px 8px 6px -2px rgba(34, 60, 80, 0.2);
  }
  button:active {
    transform: translateY(3px);
  }
</style>