<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Resume</title>
  <style>
    /* CSS styles go here */
    /* Reset default margin and padding */
    body,
    h1,
    h2,
    h3,
    p,
    ul,
    li {
      margin: 0;
      padding: 0;
    }

    /* Set a background color and text color for the body */
    body {
      background-color: #f1f1f1;
      color: #333;
      font-family: Arial, sans-serif;
    }

    /* Style the header section */
    header {
      text-align: center;
      padding: 20px;
      background-color: #fff;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }

    /* Style the introduction section */
    #introduction {
      background-color: #fff;
      padding: 20px;
      margin-bottom: 20px;
    }

    #introduction h2 {
      font-size: 18px;
      margin-bottom: 10px;
    }

    #introduction ul {
      list-style-type: none;
    }

    /* Style the education section */
    #education {
      background-color: #fff;
      padding: 20px;
      margin-bottom: 20px;
    }

    #education h2 {
      font-size: 18px;
      margin-bottom: 10px;
    }

    /* Style the skills section */
    #skills {
      background-color: #fff;
      padding: 20px;
      margin-bottom: 20px;
    }

    #skills h2 {
      font-size: 18px;
      margin-bottom: 10px;
    }

    /* Style the work experience section */
    #work-experience {
      background-color: #fff;
      padding: 20px;
      margin-bottom: 20px;
    }

    #work-experience h2 {
      font-size: 18px;
      margin-bottom: 10px;
    }

    /* Style the projects section */
    #projects {
      background-color: #fff;
      padding: 20px;
      margin-bottom: 20px;
    }

    #projects h2 {
      font-size: 18px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <!-- Content goes here -->
  <header>
    <h1>Resume</h1>
  </header>

  <section id="introduction">
    <h2>Introduction</h2>
    <ul>
      <li><strong>Name:</strong> Douglous Sobei</li>
      <li><strong>Profession:</strong> Data Analyst | Software Engineer</li>
      <li><strong>Profile Picture:</strong> <img class="profile-picture" src="./images/profile.jpeg" alt="Profile Picture"></li>
    </ul>
  </section>

  <section id="education">
    <h2>Education</h2>
    <ul>
      <li>
        <strong>Bachelor of Public Management and Development</strong><br>
        Jomo Kenyatta University of Agriculture and Technology
      </li>
      <li>
        <strong>Nano Degree in Data Analysis</strong><br>
        Data Analysis Program - ALX<br>
        Issued by: ALX Africa
      </li>
      <li>
        <strong>Nano Degree in Software Engineering</strong><br>
        Software Engineering Program - ALX<br>
        Issued by: ALX Africa
      </li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Data Analysis</li>
      <li>Python</li>
      <li>SQL</li>
      <li>HTML/CSS</li>
      <li>JavaScript</li>
      <li>Django</li>
      <li>React</li>
    </ul>
  </section>

  <section id="work-experience">
    <h2>Work Experience</h2>
    <ul>
      <li>
        <strong>Data Analyst Intern</strong><br>
        Company Name, City, Country<br>
        Date - Date<br>
        - Conducted data cleaning and preprocessing tasks<br>
        - Performed statistical analysis and created visualizations<br>
        - Collaborated with team members to develop data-driven solutions
      </li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>
        <strong>eCommerce Web Application (Django & React)</strong><br>
        - Built a full-stack eCommerce web application using Django and React.<br>
        - Developed the backend using Django to handle product management, user authentication, and order processing.<br>
        - Implemented RESTful APIs for frontend communication and data retrieval.<br>
        - Designed and developed the frontend using React, including the user interface, product listing, cart functionality, and checkout process.<br>
        - Integrated payment gateways and order tracking functionalities.<br>
        - Implemented responsive design and optimized performance for a smooth user experience.
      </li>
    </ul>
  </section>

  <!-- Code injected by live-server -->
  <script>
    // JavaScript code for live reload functionality
  </script>
</body>
</html>
