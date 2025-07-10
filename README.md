# RESUME
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Allan Joshua Manalo - Resume</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 2em 1em;
    }

    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      margin-bottom: 10px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    header p {
      font-style: italic;
      color: #ccc;
    }

    section {
      padding: 2em;
      margin: 1em auto;
      max-width: 800px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    section h2 {
      border-bottom: 2px solid #2c3e50;
      padding-bottom: 5px;
      margin-bottom: 1em;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      padding: 5px 0;
    }

    .contact-form input, .contact-form textarea, .comment-form input, .comment-form textarea {
      width: 100%;
      padding: 10px;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact-form button, .comment-form button {
      background: #2c3e50;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .contact-form button:hover, .comment-form button:hover {
      background: #1abc9c;
    }

    .download-btn {
      display: inline-block;
      background: #2980b9;
      color: white;
      padding: 10px 15px;
      margin-top: 10px;
      border-radius: 5px;
      text-decoration: none;
    }

    .download-btn:hover {
      background: #3498db;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8em;
      }

      section {
        margin: 1em;
        padding: 1em;
      }
    }
  </style>
</head>
<body>

  <!-- 🧑‍🎓 Header -->
  <header>
    <img src="https://via.placeholder.com/120" alt="Profile Picture">
    <h1>Allan Joshua Manalo</h1>
    <p>Aspiring Web Developer | Creative Thinker | Problem Solver</p>
    <a class="download-btn" href="Allan-Joshua-Manalo-Resume.pdf" download>📄 Download Resume</a>
  </header>

  <!-- 👤 About Me -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a passionate and driven individual with a keen interest in web development, design, and building digital solutions. 
      I enjoy solving problems, learning new technologies, and collaborating on creative projects. My goal is to become a full-stack web developer and contribute to innovative tech teams.
    </p>
  </section>

  <!-- 🎓 Education -->
  <section id="education">
    <h2>Education</h2>
    <ul>
      <li><strong>BS in Information Technology</strong> - University of XYZ (2020 - 2024)</li>
      <li><strong>Front-End Web Development Course</strong> - freeCodeCamp</li>
      <li><strong>JavaScript & React Bootcamp</strong> - Udemy</li>
    </ul>
  </section>

  <!-- 🛠️ Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML5, CSS3, JavaScript</li>
      <li>Responsive Web Design</li>
      <li>Teamwork & Collaboration</li>
      <li>Git & GitHub</li>
      <li>Problem Solving & Debugging</li>
    </ul>
  </section>

  <!-- 💼 Projects or Experience -->
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Portfolio Website:</strong> Personal portfolio built with HTML, CSS, JS showcasing projects and resume.</li>
      <li><strong>Task Manager App:</strong> A to-do app built with JavaScript that supports CRUD operations.</li>
      <li><strong>Weather Dashboard:</strong> Fetches real-time weather data using a public API and displays user input city weather.</li>
    </ul>
  </section>

  <!-- 📫 Contact Me -->
  <section id="contact">
    <h2>Contact Me</h2>
    <form class="contact-form">
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <!-- 💬 Comment Section -->
  <section id="comments">
    <h2>Leave a Comment</h2>
    <form class="comment-form">
      <input type="text" placeholder="Your Name"
