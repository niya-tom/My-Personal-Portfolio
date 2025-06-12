<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Niya Tom | Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f9f9ff;
      color: #333;
    }

    header {
      background: linear-gradient(to right, #667eea, #764ba2);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }

    header img {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 4px solid white;
      margin-bottom: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 2.8rem;
      margin: 10px 0 5px;
    }

    header p {
      font-size: 1.1rem;
      opacity: 0.9;
    }

    nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      background: white;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      padding: 15px 20px;
      color: #333;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: #667eea;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }

    section h2 {
      font-size: 2rem;
      color: #667eea;
      margin-bottom: 20px;
      border-left: 5px solid #667eea;
      padding-left: 15px;
    }

    ul {
      margin-left: 25px;
      line-height: 1.8;
      font-size: 1.05rem;
    }

    footer {
      background: #f0f0f0;
      padding: 20px;
      text-align: center;
      font-size: 0.9rem;
      color: #666;
    }

    .intro-box {
      background: #ffffff;
      padding: 30px;
      margin-top: -40px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.05);
      border-radius: 15px;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
    }

    .intro-box h3 {
      font-weight: 500;
      font-size: 1.2rem;
      margin-bottom: 0;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      nav a {
        padding: 10px;
        font-size: 0.95rem;
      }

      section {
        padding: 40px 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://media.licdn.com/dms/image/v2/D4D03AQFa1wWLzarUHQ/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1725599283818?e=2147483647&v=beta&t=VDqi8SfUQE1rcX5BklZOKOzTrl9cXWCALvpGUytpdoI" alt="Niya Tom Profile">
    <h1>Niya Tom</h1>
    <p>Creative Tech Enthusiast & Aspiring Software Engineer</p>
  </header>

  <div class="intro-box">
    <h3>Hello! I’m Niya — passionate about building innovative software, solving real-world problems, and exploring the world of technology. This portfolio showcases my skills, hobbies, and achievements!</h3>
  </div>

  <nav>
    <a href="#skills">Skills</a>
    <a href="#interests">Interests</a>
    <a href="#hobbies">Hobbies</a>
    <a href="#certifications">Certifications</a>
  </nav>

  <section id="skills">
    <h2>💻 Technical Skills</h2>
    <ul>
      <li><strong>Languages:</strong> Python, Java, C, JavaScript</li>
      <li><strong>Frontend:</strong> HTML, CSS, React (Basics)</li>
      <li><strong>Backend:</strong> Node.js (Beginner), APIs</li>
      <li><strong>Database:</strong> MySQL, MongoDB</li>
      <li><strong>Tools:</strong> Git, GitHub, Postman, VS Code</li>
      <li><strong>Concepts:</strong> Data Structures & Algorithms, Object-Oriented Programming</li>
    </ul>
  </section>

  <section id="interests">
    <h2>📌 Interests</h2>
    <ul>
      <li>Web and Mobile App Development</li>
      <li>Artificial Intelligence and Machine Learning</li>
      <li>UI/UX Design and Human-Computer Interaction</li>
      <li>Open Source Contributions and Community Projects</li>
      <li>Hackathons and Tech Meetups</li>
    </ul>
  </section>

  <section id="hobbies">
    <h2>🎨 Hobbies</h2>
    <ul>
      <li>Sketching, Doodling and Digital Art</li>
      <li>Tech Blogging and Writing Tutorials</li>
      <li>Listening to Podcasts and Audiobooks</li>
      <li>Exploring Nature & Photography</li>
      <li>Learning New Programming Tools and Frameworks</li>
    </ul>
  </section>

  <section id="certifications">
    <h2>📜 Certifications</h2>
    <ul>
      <li>💻 Responsive Web Design – freeCodeCamp</li>
      <li>☕ Java Programming – HackerRank Certified</li>
      <li>🧠 AI For Everyone – Coursera (Andrew Ng)</li>
      <li>🐍 Python Programming Basics – Great Learning</li>
      <li>📂 Git & GitHub for Beginners – Udemy</li>
    </ul>
  </section>

  <footer>
    © 2025 Niya Tom • Crafted with ❤️ using HTML, CSS & JavaScript
  </footer>

</body>
</html>
