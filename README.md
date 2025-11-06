<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guruvu Galla Hari | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f7fb;
      color: #333;
      line-height: 1.6;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, #007bff, #6610f2);
      color: white;
      text-align: center;
      padding: 70px 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      position: relative;
    }

    header h1 {
      font-size: 2.8em;
      font-weight: 600;
      animation: fadeInDown 1s ease;
    }

    header p {
      font-size: 1.3em;
      margin-top: 10px;
      animation: fadeInUp 1.2s ease;
    }

    @keyframes fadeInDown {
      from {opacity: 0; transform: translateY(-30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    /* Section Styling */
    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 40px 30px;
      background: white;
      border-radius: 15px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    section:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.15);
    }

    h2 {
      color: #0d6efd;
      border-left: 5px solid #6610f2;
      padding-left: 10px;
      margin-bottom: 20px;
      font-size: 1.8em;
    }

    ul {
      list-style: none;
      padding-left: 10px;
    }

    ul li {
      margin-bottom: 10px;
    }

    strong {
      color: #222;
    }

    /* Contact Links */
    .contact a {
      color: #6610f2;
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }

    .contact a:hover {
      color: #0d6efd;
      text-shadow: 0 0 10px rgba(13, 110, 253, 0.6);
    }

    /* Footer */
    footer {
      background: linear-gradient(135deg, #6610f2, #007bff);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
      box-shadow: 0 -3px 15px rgba(0,0,0,0.2);
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }
      header p {
        font-size: 1em;
      }
      section {
        padding: 25px;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Guruvu Galla Hari</h1>
    <p>BCA Student | Aspiring Full Stack Developer</p>
  </header>

  <!-- About -->
  <section>
    <h2>About Me</h2>
    <p>
      I am a BCA student at <strong>Sri Hari Degree College (Autonomous), Kadapa</strong> with a deep interest
      in <strong>Web Development, Databases, and Full Stack technologies</strong>. Currently doing an internship
      in Full Stack Web Development at <strong>Edutanr</strong>. I enjoy building real-world applications and
      continuously learning new technologies to improve my skills.
    </p>
  </section>

  <!-- Education -->
  <section>
    <h2>Education</h2>
    <ul>
      <li><strong>BCA – Sri Hari Degree College (Autonomous), Kadapa</strong> (2024 – 2027 Expected)</li>
    </ul>
  </section>

  <!-- Skills -->
  <section>
    <h2>Skills</h2>
    <ul>
      <li>💻 Programming: C, C++, Python, JavaScript</li>
      <li>🌐 Web: HTML, CSS, Node.js, React.js</li>
      <li>🗄 Database: MySQL, MongoDB</li>
      <li>🔧 Tools: Git, GitHub</li>
    </ul>
  </section>

  <!-- Projects -->
  <section>
    <h2>Projects</h2>
    <ul>
      <li><strong>🛒 E-Commerce Website:</strong> Built using React.js, Node.js, and MongoDB with user authentication.</li>
      <li><strong>📱 Student Attendance App:</strong> Designed for Sri Hari Degree College using MySQL and Node.js backend.</li>
      <li><strong>🌾 Smart Crop Suggestion System:</strong> Suggests best crops based on soil and climate data.</li>
    </ul>
  </section>

  <!-- Experience -->
  <section>
    <h2>Experience</h2>
    <ul>
      <li><strong>Internship at Edutanr</strong> – Full Stack Web Development Intern (2025)</li>
    </ul>
  </section>

  <!-- Contact -->
  <section class="contact">
    <h2>Contact</h2>
    <p>📧 Email: <a href="mailto:g.hari9705@gmail.com">g.hari9705@gmail.com</a></p>
    <p>🔗 LinkedIn: <a href="https://www.linkedin.com/in/guruvu-galla-hari" target="_blank">linkedin.com/in/guruvu-galla-hari</a></p>
    <p>💻 GitHub: <a href="https://github.com/harig9" target="_blank">github.com/harig9</a></p>
    <p>📍 Location: Kadapa, Andhra Pradesh</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Guruvu Galla Hari | Designed with 💙 by Hari</p>
  </footer>

</body>
</html>