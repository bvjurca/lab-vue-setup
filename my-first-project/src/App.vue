<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <div id="app">
    <h1>To-Do List</h1>
    <ul>
      <li>
        <to-do-item></to-do-item>
      </li>
    </ul>
  </div>

  <router-view/>
</template>

<script>

import ToDoItem from './components/ToDoItem.vue';

export default {
  name: 'App',
  components: {
    ToDoItem,
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
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

ul li {
  list-style: none;
}
</style>
