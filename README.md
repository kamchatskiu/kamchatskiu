<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My One-Page Website</title>
    <link rel="stylesheet" href="styles.css">
    <div id="sidebar" class="sidebar">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a class="active" href="#intro">Intro</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="intro">
        <h1>Welcome to My One-Page Website</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
      </section>
      <section id="services">
        <h2>My Services</h2>
        <ul>
          <li>
            <h3>Service 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
          <li>
            <h3>Service 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
          <li>
            <h3>Service 3</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
        </ul>
      </section>
      <section id="portfolio">
        <h2>My Portfolio</h2>
        <ul>
          <li>
            <img src="image1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
          <li>
            <img src="image2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
          <li>
            <img src="image3.jpg" alt="Project 3">
            <h3>Project 3</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod, nibh vel laoreet laoreet, velit velit gravida massa, vel porta nunc velit velit velit.</p>
          </li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contact Me</h2>
        <form>
          <label for="name">Name:</label>
          <input type="text" id="name" name="name">
          <label for="email">Email:</label>
          <input type="email" id="email" name="email">
          <label for="message">Message:</label>
          <textarea id="message" name="message"></textarea>
          <button type="submit">Send</button>
        </form>
      </section>
    </main>
    <footer>
      <p>&copy; 2023 My One-Page Website</p>
    </footer>
  </body>
</html>      
