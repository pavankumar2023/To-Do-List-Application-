<template>
    <div class="userpage">
      <h1>Welcome, Pavan Kumar!</h1>
      <p>This is your user profile page.</p>
      <!-- Display user information here -->
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        username: 'User', // Replace this with actual user data
        // Other user data properties...
      }
    },
    created() {
      // Fetch user data when component is created
      // this.username = fetchUserData() or similar
    }
  }
  </script>
  
  <style scoped>
  .user {
    text-align: center;
    background-color: rgb(238, 110, 110);
  }
  
  .user h1 {
    background-color: rgb(71, 233, 26);

    margin-top: 50px; 
  }
  
  .user p {
    margin: 50px;
    width: 100%;
    background-color: black;
  }
  </style>
  