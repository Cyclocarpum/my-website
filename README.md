<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles/style.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Welcome! I am [Your Name], an [Your Profession].</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Here are a few of my projects:</p>
    <ul>
      <li>Project 1: <a href="#">View Details</a></li>
      <li>Project 2: <a href="#">View Details</a></li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email me at <a href="mailto:youremail@example.com">youremail@example.com</a></p>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: example@example.com</p>
    
<section id="contact">
  <h2>Contact</h2>
  <p>Email: example@example.com</p>
  
  <h3>Leave a Comment</h3>
  <form id="comment-form">
    <label for="name">Your Name:</label><br>
    <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
    
  <label for="comment">Your Comment:</label><br>
    
  <textarea id="comment" name="comment" rows="5" placeholder="Write your comment here" required></textarea><br><br>
    <button type="submit">Submit</button>
  </form>
</section>
<section id="animation">
  <h2>Watch the Moving Ball!</h2>
  <p>Here’s a fun animation of a ball that moves back and forth.</p>
  
  <div class="ball"></div>
</section>

<style>
  /* Styling for the animation section */
  #animation {
    text-align: center;
    margin: 50px 0;
    padding: 20px;
    background: #f7f7f7;
    border: 1px solid #ddd;
    border-radius: 10px;
  }

  #animation h2 {
    font-size: 24px;
    color: #333;
  }

  #animation p {
    font-size: 16px;
    color: #555;
  }

  /* Create the ball */
  .ball {
    width: 50px;
    height: 50px;
    background-color: red;
    border-radius: 50%;
    margin: 20px auto;
    position: relative;
    animation: moveBall 2s linear infinite;
  }

  /* Keyframes for the animation */
  @keyframes moveBall {
    0% {
      transform: translateX(0);
    }
    50% {
      transform: translateX(200px); /* Moves to the right */
    }
    100% {
      transform: translateX(0); /* Moves back to the start */
    }
  }
</style>
  
  <footer>
    <p>&copy; 2025 [Your Name]. All Rights Reserved.</p>
  </footer>
</body>
</html>
