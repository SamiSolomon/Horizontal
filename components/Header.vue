<template>
    <header class="header-container">
      <div class="logo">Udemy</div>
      <input type="text" placeholder="Search for anything" class="search-bar" />
      <nav class="nav-links">
        <a href="#">Udemy Business</a>
        <a href="#">Teach on Udemy</a>
      </nav>
      <div class="actions">
        <button class="cart-button">🛒</button>
        <button class="login-button">Log in</button>
        <button class="signup-button">Sign up</button>
        <button class="language-button">🌐</button>
      </div>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header',
  };
  </script>
  
  <style scoped>
  .header-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 20px;
    border-bottom: 1px solid #e0e0e0;
  }
  .logo {
    font-size: 24px;
    font-weight: bold;
    color: #5624d0; /* Matches the Udemy brand color */
  }
  .search-bar {
    flex-grow: 1;
    margin: 0 15px;
    padding: 8px 12px;
    border: 1px solid #ccc;
    border-radius: 20px;
    max-width: 400px;
  }
  .nav-links a {
    margin-right: 15px;
    text-decoration: none;
    color: #333;
    font-size: 16px;
  }
  .actions {
    display: flex;
    align-items: center;
  }
  .cart-button, .login-button, .signup-button, .language-button {
    margin-left: 10px;
    padding: 5px 10px;
    border: none;
    background: none;
    cursor: pointer;
    font-size: 16px;
  }
  .signup-button {
    background-color: #333;
    color: #fff;
    border-radius: 4px;
    padding: 6px 12px;
  }
  </style>
  