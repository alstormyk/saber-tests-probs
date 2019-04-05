<template>
  <nav>
    <h1>Hello</h1>
    <ul>
      <li><saber-link to="/">Home</saber-link></li>
      <li><saber-link to="/about.html">About me</saber-link></li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  height: 30px;
  align-items: center;
  padding: 0.7rem 1.5rem;
  line-height: 2rem; 
  border-bottom: 3px solid #f0f0f0;
}
ul {
  display: flex;
}
li {
    padding-left: 1.5rem;
    box-sizing: border-box;
    right: 0.7rem;
    top: 1.5rem;
    display: flex;
}
li a {
  display: inline-block;
  margin-left: 1.5rem;
}
</style>