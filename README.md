# Resume-



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Portfolio of Maulik Pratap Singh - BBA Student, Digital Entrepreneur, and Creative Enthusiast." />
  <title>Maulik Pratap Singh | Portfolio</title>
  <style>
    :root {
      --lilac: #c8a2c8;
      --bright-blue: #007acc;
      --hover-blue: #005f99;
      --dark-bg: #121212;
      --light-bg: #fdfdff;
      --dark-text: #f5f5f5;
      --light-text: #222;
      --card-bg: #ffffff;
      --card-dark-bg: #1f1f1f;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--light-bg);
      color: var(--light-text);
      transition: background 0.3s, color 0.3s;
    }

    header {
      background: var(--bright-blue);
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .toggle {
      background-color: var(--hover-blue);
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      cursor: pointer;
      border-radius: 5px;
    }

    .profile {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 2rem auto 1rem;
    }

    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 1rem;
      display: grid;
      gap: 2rem;
    }

    .block {
      background: var(--card-bg);
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: background 0.3s, color 0.3s;
    }

    h2 {
      color: var(--bright-blue);
      transition: color 0.3s;
    }

    h2:hover {
      color: var(--hover-blue);
    }

    ul {
      padding-left: 1.2rem;
    }

    li {
      margin-bottom: 0.5rem;
    }

    .btn {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      background-color: var(--bright-blue);
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: var(--hover-blue);
    }

    /* Dark Mode Styles */
    .dark {
      background-color: var(--dark-bg);
      color: var(--dark-text);
    }

    .dark header {
      background: var(--lilac);
    }

    .dark .block {
      background: var(--card-dark-bg);
    }

    .dark h2 {
      color: var(--lilac);
    }

    .dark h2:hover {
      color: var(--bright-blue);
    }

    .dark .btn {
      background-color: var(--lilac);
    }

    .dark .btn:hover {
      background-color: var(--bright-blue);
    }
  </style>
</head>
<body>
  <header>
    <h1>Maulik Pratap Singh</h1>
    <button class="toggle" onclick="toggleTheme()">Toggle Theme</button>
  </header>

  <main>
    <section class="profile">
      <img src="profile.jpg" alt="Maulik Pratap Singh Profile Picture">
    </section>

    <div class="container">
      <section class="block">
        <h2>About Me</h2>
        <p>Student with dreams and hopes to achieve everything.</p>
      </section>

      <section class="block">
        <h2>Skills</h2>
        <ul>
          <li>HTML</li>
          <li>Python</li>
          <li>Microsoft Office</li>
          <li>Editing</li>
          <li>Content Writing</li>
          <li>Painting</li>
          <li>Poetry</li>
          <li>Public Speaking</li>
        </ul>
      </section>

      <section class="block">
        <h2>Education</h2>
        <p>12th Pass, currently pursuing BBA (Digital Business & Entrepreneurship) from IIM Bangalore.</p>
      </section>

      <section class="block">
        <h2>Achievements</h2>
        <ul>
          <li>City-level winner – Speech & Debate</li>
          <li>8th position in All-India Painting Competition</li>
          <li>City-level Quiz Winner</li>
          <li>Entrepreneurship Competition – City & Block Level</li>
          <li>City-level Football Champion</li>
        </ul>
      </section>

      <section class="block">
        <h2>Contact</h2>
        <a href="mailto:purendrapratapsingh567@gmail.com" class="btn">Email Me</a><br><br>
        <a href="https://www.linkedin.com/in/maulik-pratap-singh-68a632280/" target="_blank" class="btn">Visit LinkedIn</a>
      </section>
    </div>
  </main>

  <script>
    function toggleTheme() {
      document.body.classList.toggle('dark');
    }
  </script>
</body>
</html>


