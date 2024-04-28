<template>
    <div class="home">
      <h1>Welcome to Our Website!</h1>
      <p>This is the homepage of our Todo list application.</p>
      <router-link to="/TodoList">Click here for Todo List</router-link>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomePage',
    data() {
      return {
        // Your data properties here...
      }
    },
    methods: {
      // Your methods here...
    }
  }
  </script>
  
  <style scoped>
  .home {
    text-align: center;
    background-color: rgba(232, 239, 238, 0.032);
    background-size: 100px;
  }
  
  .home h1 {
    margin-top: 50px;
  }
  
  .home p {
    margin: 25px auto;
    width: 50%;
  }
  
  .home a {
    padding: 15px 15px;
    border: 1px solid #333;
    border-radius: 20px;
    text-decoration: none;
    color: #333;
  }
  
  .home a:hover {
    background-color: #3a6900;
    color: #d0dddf;
  }


</style>
  