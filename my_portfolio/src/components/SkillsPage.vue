<template>
    <div class="skills">
      <h1>My Skills</h1>
      <p>Here are some of the skills I have acquired over time:</p>
      <ul>
        <li>HTML & CSS: Building responsive and well-structured web pages.</li>
        <li>JavaScript: Adding interactivity and logic to websites.</li>
        <li>Vue.js: Developing dynamic single-page applications.</li>
        <li>PHP: Building server-side applications and handling database interactions.</li>
        <li>SQL: Working with databases and writing queries for data manipulation.</li>
        <li>Git: Version control and collaboration using Git and GitHub.</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'SkillsPage',
  }
  </script>
  
  <style scoped>
  .skills {
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
    font-size: 1.2rem;
    color: #555;
    margin: 10px 0;
  }
  </style>
  