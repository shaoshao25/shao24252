<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css"> <!-- Link to CSS file -->
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
  </header>
  
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
  
  <section id="about">
    <h2>About Me</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum eu sapien at leo luctus auctor a sed libero.</p>
  </section>
  
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ul>
  </section>
  
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Project 1</li>
      <li>Project 2</li>
      <li>Project 3</li>
    </ul>
  </section>
  
  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Send</button>
    </form>
  </section>
  
  <footer>
    <p>&copy; 2021 My Portfolio. All rights reserved.</p>
  </footer>
</body>
</html>

CSS (style.css):

/* Global styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

/* Header styles */
h1 {
  text-align: center;
}

/* Navigation styles */
nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  background-color: #333;
}

nav ul li {
  margin: 0 10px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
}

nav ul li a:hover {
  background-color: #555;
}

/* Section styles */
section {
  padding: 50px;
  text-align: center;
}

section h2 {
  margin-bottom: 20px;
}

/* Form styles */
form label {
  display: block;
}

form input, form textarea {
  width: 100%;
  margin-bottom: 10px;
}

form button {
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}

form button:hover {
  background-color: #555;
}

/* Footer styles */
footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px;
}
