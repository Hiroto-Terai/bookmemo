<template>
  <div class="header-main">
    <div class="logo">
      <h1>BookMemo</h1>
    </div>
    <nav class="navbar">
      <ul>
        <li>
          <router-link to="/" class="routerlink">Home</router-link>
        </li>
        <li>
          <router-link to="/about" class="routerlink">About</router-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header-main {
  max-width: 1170px;
  width: 100%;
  font-family: optima;
  color: #fff;
  display: flex;
  background-color: #000;
  position: fixed;
  top: 0;
  z-index: 100;
}

.logo {
  width: 30%;
  justify-content: left;
  padding-left: 25px;
}

.navbar {
  justify-content: flex-end;
  display: flex;
  width: 70%;
}

ul {
  display: flex;
  justify-content: right;
  padding: 0;
  margin: 0;
  list-style: none;
}

li {
  width: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.routerlink {
  color: #fff;
  text-decoration: none;
}
</style>
