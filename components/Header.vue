<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
        </li>
    </ul>
  </header>
</template>

<style scoped>
.header{
  width:100%;
  height:60%;
  display: flex;
  justify-content: center;
  align-items:center;
  background-color: #cfdb;
}
.nav-items{
  list-style: none;
  padding: 0;
  margin:0;
  display:flexbox;
  justify-content: space-around;
  align-items: center;
  width:80%;
}
.nav-items a {
  text-decoration: none;
  font-weight:600;
  color:white;

}
.nav-items a:hover,
.nav-items a:active {
   color:blueviolet;
}
</style>
