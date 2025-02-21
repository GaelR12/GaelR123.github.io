<template>
    <div class="projects">
      <h1>My Projects</h1>
      <p>Here are some of the projects I have worked on:</p>
      <ul>
        <li>
          <strong>Project 1:</strong> Website for local business
          <p>Description: Built a responsive website for an HVAC company using Vue.js and Bootstrap.</p>
        </li>
        <li>
          <strong>Project 2:</strong> Personal Portfolio
          <p>Description: Created my personal portfolio site to showcase my skills and projects.</p>
        </li>
        <li>
          <strong>Project 3:</strong> Book Inventory System
          <p>Description: Developed a book inventory management system using C# and ASP.NET Core.</p>
        </li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ProjectsPage',
  }
  </script>
  
  <style scoped>
  .projects {
    padding: 20px;
    text-align: center;
  }
  
  h1 {
    color: #333;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    background-color: #f4f4f4;
    margin: 10px 0;
    padding: 10px;
    border-radius: 5px;
  }
  
  strong {
    color: #007BFF;
  }
  
  p {
    font-size: 1rem;
    color: #555;
  }
  </style>
  