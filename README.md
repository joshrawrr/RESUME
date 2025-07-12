<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Allan Joshua C. Manalo - Resume</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #4a90e2;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    header p {
      margin-top: 5px;
      font-style: italic;
    }
    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
      background: white;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    h2 {
      border-bottom: 2px solid #4a90e2;
      padding-bottom: 5px;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    li::before {
      content: "✔️ ";
      color: #4a90e2;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .contact-form button {
      background-color: #4a90e2;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .comment-section input, .comment-section textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .comment-section button {
      background-color: #4a90e2;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .download-btn {
      display: inline-block;
      margin-top: 10px;
      background-color: #4a90e2;
      color: white;
      padding: 10px;
      text-decoration: none;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Allan Joshua C. Manalo</h1>
    <p>Creative Thinker | Problem Solver</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>I am a motivated and passionate individual aiming to grow in the field of web development. I enjoy solving problems, learning new technologies, and turning ideas into functional websites.</p>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>Dominican College of Tarlac - BS Information Technology</li>
      <li>Web Development Courses (HTML, CSS, JavaScript)</li>
    </ul>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Multimedia Design</li>
      <li>Responsive Web Design</li>
      <li>Teamwork</li>
    </ul>
  </section>

  <section>
    <h2>Projects or Experience</h2>
    <ul>
      <li>Personal Portfolio Website</li>
      <li>A Menu List</li>
      <li>Sinigang Recipe</li>
        <li>Simple Calculator</li>
    </ul>
  </section>

  <section class="contact-form">
    <h2>Contact Me</h2>
    <input type="email" placeholder="Your Email">
    <textarea rows="4" placeholder="Your Message"></textarea>
    <button onclick="alert('Message Sent!')">Send</button>
    <p>Or reach me at: 0963-708-1134</p>
    <a href="#" class="download-btn">Download Resume</a>
  </section>

  <section class="comment-section">
    <h2>Leave a Comment</h2>
    <input type="text" placeholder="Your Name">
    <textarea rows="3" placeholder="Your Comment"></textarea>
    <button onclick="alert('Comment Submitted!')">Submit</button>
  </section>

</body>
</html>
