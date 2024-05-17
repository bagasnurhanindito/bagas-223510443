<template>
    <aside class="sidebar">
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </aside>
  </template>
  
  <script>
  export default {
    name: 'SidebarComponent'
  }
  </script>
  
  <style scoped>
  .sidebar {
    background-color: #f8f9fa;
    padding: 20px;
    border-right: 1px solid #ddd;
  }
  
  .sidebar nav ul {
    list-style-type: none;
    padding: 0;
  }
  
  .sidebar nav ul li {
    margin: 10px 0;
  }
  
  .sidebar nav ul li a {
    text-decoration: none;
    color: #007bff;
  }
  </style>
  