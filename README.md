# Resume-
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maulik Pratap Singh | Portfolio</title>
  <style>
    :root {
      --lilac: #c8a2c8;
      --bright-blue: #007acc;
      --hover-blue: #005f99;
      --dark-bg: #121212;
      --light-bg: #f5f5f5;
      --dark-text: #e0e0e0;
      --light-text: #222;
      --card-bg: #ffffff;
      --card-dark-bg: #1f1f1f;
    }body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  transition: background 0.3s, color 0.3s;
  background: var(--light-bg);
  color: var(--light-text);
}

header {
  background: var(--bright-blue);
  color: #fff;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.toggle {
  cursor: pointer;
  padding: 0.5rem 1rem;
  background: var(--hover-blue);
  border: none;
  color: white;
  border-radius: 5px;
}

.container {
  padding: 2rem;
  max-width: 1000px;
  margin: auto;
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}

.block {
  padding: 1.5rem;
  border-radius: 15px;
  background-color: var(--card-bg);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: background 0.3s, color 0.3s;
}

h1, h2 {
  color: var(--bright-blue);
  transition: color 0.3s;
}

h2:hover {
  color: var(--hover-blue);
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 0.5rem;
}

.btn {
  display: inline-block;
  margin: 0.5rem 0.5rem 0 0;
  padding: 0.5rem 1rem;
  border: none;
  background: var(--bright-blue);
  color: white;
  border-radius: 4px;
  text-decoration: none;
  transition: background 0.3s;
}

.btn:hover {
  background: var(--hover-blue);
}

.dark {
  background: var(--dark-bg);
  color: var(--dark-text);
}

.dark header {
  background: var(--lilac);
}

.dark .btn {
  background: var(--lilac);
}

.dark .btn:hover {
  background: var(--bright-blue);
}

.dark h2:hover {
  color: var(--lilac);
}

.dark .block {
  background-color: var(--card-dark-bg);
}

  </style>
</head>
<body>
  <header>
    <h1>Maulik Pratap Singh</h1>
    <button class="toggle" onclick="toggleMode()">Toggle Theme</button>
  </header>  <div class="container">
    <div class="block">
      <h2>About Me</h2>
      <p>Student with dreams and hopes to achieve everything.</p>
    </div><div class="block">
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
</div>

<div class="block">
  <h2>Education</h2>
  <p>12th Pass, currently pursuing BBA DBE from IIM Bangalore</p>
</div>

<div class="block">
  <h2>Achievements</h2>
  <ul>
    <li>City level winner - Speech & Debate</li>
    <li>8th All-India Painting Competition</li>
    <li>City level Quiz Winner</li>
    <li>Entrepreneurship Competition - City & Block Level</li>
    <li>City Level Football Champion</li>
  </ul>
</div>

<div class="block">
  <h2>Contact</h2>
  <a href="mailto:purendrapratapsingh567@gmail.com" class="btn">Email Me</a>
  <a href="https://www.linkedin.com/in/maulik-pratap-singh-68a632280/" target="_blank" class="btn">View LinkedIn</a>
</div>

  </div>  <script>
    function toggleMode() {
      document.body.classList.toggle('dark');
    }
  </script></body>
</html>